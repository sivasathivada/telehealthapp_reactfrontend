# HealthApp Frontend (React + Vite)

A modern, high-performance tele-health frontend application built with **React** and **Vite**. This platform enables seamless, real-time doctor-patient interactions, secure medical consultations, and integrated billing workflows.

---

## 🚀 Key Features

*   **⚡ Ultra-Fast Build System:** Powered by Vite for near-instantaneous Hot Module Replacement (HMR) and optimized production builds.
*   **🔌 Real-Time Synced Communications:** Native WebSocket integration ensuring instant messaging, live chat notifications, and real-time medical updates.
*   **🎥 HD Audio/Video Consultations:** Secure, low-latency peer-to-peer video and audio calling directly inside the browser.
*   **💳 Secure Payment Gateway:** Fully integrated with Stripe API for secure appointment billing, subscriptions, and transaction management.

---

## 📸 Screenshots

<details>
  <summary>📸 Click to view Application Previews</summary>
  
  ## Patient Dashboard & Doctor Dashboard

<img width="1920" height="1080" alt="Screenshot (9)" src="https://github.com/user-attachments/assets/e95b0a33-afb4-47ef-8d55-40e48be52cdd" />
<img width="1920" height="1080" alt="Screenshot (8)" src="https://github.com/user-attachments/assets/0c0f85de-77a3-4c3f-a9da-f6c166aa87cf" />
<img width="1920" height="1080" alt="Screenshot (11)" src="https://github.com/user-attachments/assets/160b7281-533a-4886-b6c5-930e89c2ab6d" />

 ## Live Video Consultation Room
 <img width="1920" height="1080" alt="Screenshot (14)" src="https://github.com/user-attachments/assets/9e6ac6b7-425f-40e8-8494-05390b32a17e" />
 <img width="1920" height="1080" alt="Screenshot (15)" src="https://github.com/user-attachments/assets/edcf4130-25ca-4940-8aa9-e98495a65033" />

  ## Secure Checkout Checkout
 
</details>

---

## 🛠️ Tech Stack

*   **Core Framework:** React 19 / 18
*   **Build Tool & Bundler:** Vite
*   **Real-Time Architecture:** WebSockets / WebRTC (for audio-video streams)
*   **Payment Processor:** Stripe Elements / Stripe JS
*   **Routing:** React Router DOM

---

## 📦 Getting Started

### Prerequisites
Make sure you have [Node.js](https://nodejs.org) (v18 or higher recommended) installed on your system.

### Installation Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd healthapp-frontend
   ```

2. **Install all dependencies:**
   ```bash
   npm install
   ```

3. **Configure Environment Variables:**
   Create a `.env` file at the root level of your project and populate it with your specific service keys:
   ```env
   VITE_API_URL=http://localhost:8000
   VITE_WEBSOCKET_URL=ws://localhost:8000/ws
   VITE_STRIPE_PUBLISHABLE_KEY=pk_test_your_key_here
   ```

4. **Launch the development server:**
   ```bash
   npm run dev
   ```
   Open your browser and navigate to `http://localhost:5173` to see the application in action.

---

## 🏗️ Project Architecture Overview

```text
src/
├── assets/          # Static media assets (logos, default avatars)
├── components/      # Reusable UI components (Buttons, Inputs, Modals)
├── hooks/           # Custom React hooks (useWebSockets, useVideoCall)
├── pages/           # View layouts (Dashboard, CallRoom, Checkout)
├── services/        # API calling suites & Stripe interface setups
├── App.jsx          # Central entry layout and route configuration
└── main.jsx         # Vite bootstrapping point
```

