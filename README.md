# SignalR Real-Time Location & Infinite Scroll App

This project showcases real-time communication with SignalR for live location sharing and an efficient infinite scroll user feed, built with Next.js and React Query.

## ✨ Key Features

*   **Real-Time Location Sharing**:
    *   **User A (Sender)**: Broadcasts live GPS coordinates (simulated or real) via SignalR.
    *   **User B (Receiver)**: Displays real-time location updates on an interactive Leaflet map.
    *   Includes a custom `useSignalR` hook, connection tester, and a mock mode for development.
*   **Infinite Scroll User Feed**:
    *   Fetches and displays a paginated list of users from an API.
    *   Uses React Query for data management, caching, and automatic retries.
    *   Features `react-window` for list virtualization, skeleton loaders, and robust error handling.
    *   Automatically scrolls to the top once all data is loaded.

## 🚀 Technologies Used

*   **Next.js 15 (App Router)**
*   **React Query**
*   **SignalR (`@microsoft/signalr`)**
*   **Leaflet (`leaflet`, `react-leaflet`)**
*   **React Window (`react-window`)**
*   **Tailwind CSS & Shadcn/ui**
*   **TypeScript**

## ⚙️ Setup and Installation

1.  **Download the Code**: If you're in v0, click "Download Code".
2.  **Install Dependencies**:
    ```bash
    npm install
