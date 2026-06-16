
# SakhiSell — Social Commerce Platform

A modern social commerce platform connecting sellers and buyers through an intuitive, mobile-first interface. Built with React, Vite, and TailwindCSS with a Figma-first design approach.

![React](https://img.shields.io/badge/React-18.3-61DAFB?style=for-the-badge&logo=react&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-6.3-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind%20CSS-4.1-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-Backend-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-Typed-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

---

## ✨ Features

- **🛍️ Buyer Discovery** — Browse and discover seller products in a social feed
- **📱 Seller Dashboard** — Post and manage products with a clean interface
- **🔄 Real-Time Product Sync** — localStorage-backed product data with instant cross-screen updates
- **🎨 Figma-First Design** — Professional UI designed in Figma and exported via Figma Make
- **📲 Mobile-First** — Responsive design optimized for mobile commerce
- **🎉 Animations** — Smooth transitions powered by the Motion library

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| **Frontend** | React 18.3, TypeScript |
| **Build Tool** | Vite 6.3 |
| **Styling** | TailwindCSS 4.1, Emotion (MUI) |
| **UI Components** | Radix UI primitives, MUI |
| **Backend** | Firebase (planned) |
| **Animations** | Motion (Framer Motion) |
| **Charts** | Recharts |
| **Routing** | React Router 7 |
| **Design** | Figma |

---

## 🚀 Getting Started

### Prerequisites

- **Node.js 18+** installed
- **pnpm** package manager ([Install pnpm](https://pnpm.io/installation))

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/SakhiSell-Social-Commerce-Platform.git
   cd SakhiSell-Social-Commerce-Platform
   ```

2. **Install dependencies**

   ```bash
   pnpm install
   ```

3. **Configure environment variables**

   Create a `.env` file in the project root:

   ```env
   VITE_FIREBASE_API_KEY=your_firebase_api_key
   VITE_FIREBASE_PROJECT_ID=your_project_id
   ```

4. **Start development server**

   ```bash
   pnpm dev
   ```

5. **Open in browser**

   Navigate to [http://localhost:5173](http://localhost:5173)

### Production Build

```bash
pnpm build
```

---

## 📖 How It Works

### Local Realtime Product Sync

The app currently runs with **localStorage-backed product data**:

- Seller product posts are saved to browser localStorage
- Buyer pages and seller dashboard subscribe to product update events
- New products appear instantly across buyer and seller screens without page refresh

> **Note**: Product data is browser-local in this mode and will not sync across different devices. Seller posts are merged with bundled demo products for buyer discovery.

---

## 📁 Project Structure

```
SakhiSell-Social-Commerce-Platform/
├── index.html              # Entry point
├── package.json            # Dependencies and scripts
├── vite.config.ts          # Vite configuration with Figma asset resolver
├── postcss.config.mjs      # PostCSS configuration
├── pnpm-workspace.yaml     # pnpm workspace config
├── guidelines/             # Design guidelines
├── dist/                   # Production build output
└── README.md
```

---



## 🎨 Design

The original design is available on Figma:
[**SakhiSell Social Commerce Platform — Figma**](https://www.figma.com/design/kdpolvEHW1vyK3kA8WvAoz/SakhiSell-Social-Commerce-Platform)

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

See [ATTRIBUTIONS.md](ATTRIBUTIONS.md) for third-party asset credits.

---

## 🙋‍♀️ Author

**Sujitha Kotyada** — [@sujitha-kotyada](https://github.com/sujitha-kotyada)
