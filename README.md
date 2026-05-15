# Oko: AI Photo Analyzer

Oko is a robust, full-stack application designed to perform intelligent image analysis. By acting as a seamless bridge between a responsive client-side interface and advanced LLM Vision APIs, Oko provides an efficient way to process, analyze, and manage visual data.

## 🚀 Core Features

*   **Intelligent Image Analysis**: Utilize cutting-edge LLM vision capabilities to extract structured information, recognize objects, and interpret visual content.
*   **Secure Orchestration**: A safe, managed bridge for frontend-to-AI-API communication, ensuring secure access and optimized orchestration.
*   **Dynamic Storage Management**: Automated handling of temporary storage with robust cleanup logic to ensure data integrity and security.
*   **Responsive RWD Architecture**: Built using a Mobile-First approach to provide a consistent experience across all device sizes.
*   **Dynamic Theming**: Highly customizable UI with generative color systems and adaptive layouts.

## 🛠 Tech Stack

### Frontend (Client)
*   **Framework**: React + Vite + TypeScript.
*   **Architecture**: Feature-Sliced Design (FSD) for high modularity.
*   **State Management**: Observer Pattern (no global state libraries).
*   **UI Foundation**: Vanilla CSS with dynamic CSS variable management.

### Backend (Server)
*   **Runtime**: Node.js + Express + TypeScript.
*   **Intelligence**: Google Generative AI (Gemini Vision).
*   **Storage**: Supabase Storage.
*   **Communication**: Secure HTTPS tunnel via Tailscale Funnel.

## 📦 Getting Started

### Prerequisites
*   Node.js (v20+)
*   Supabase project
*   Google Gemini API Key
*   Tailscale (for backend deployment)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/[your-username]/oko.git
   cd oko
   ```

2. **Setup Server:**
   ```bash
   cd my-ai-app-server
   npm install
   cp .env.example .env
   # Configure your .env with Supabase, Gemini, and API keys
   npm run start
   ```

3. **Setup Client:**
   ```bash
   cd ../my-ai-app-client
   npm install
   cp .env.example .env
   # Configure VITE_API_URL and VITE_SUPABASE_URL
   npm run dev
   ```

## 🏗 Architecture Principles
*   **Modularity**: Built on FSD principles to ensure code maintainability and feature portability.
*   **Security-First**: Strict JWT authentication and RBAC hierarchy ensure secure API interactions.
*   **Performance**: Optimized bundle sizes with lazy loading and efficient image compression utilities.

---
*Built with passion as an AI-powered image analysis platform.*
