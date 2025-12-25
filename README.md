
# :coin: CryptoVault

<div align="center">

  ![Status](https://img.shields.io/badge/Status-Live-00D084?style=for-the-badge&logo=statuspage&logoColor=white)
  ![React](https://img.shields.io/badge/React-18.2-61DAFB?style=for-the-badge&logo=react&logoColor=black)
  ![Vite](https://img.shields.io/badge/Vite-5.0-646CFF?style=for-the-badge&logo=vite&logoColor=white)
  ![Tailwind](https://img.shields.io/badge/Tailwind-3.3-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

  <br />

  **A modern, high-performance cryptocurrency tracker built for the decentralized web.**

  [**:rocket: Launch Live App**](https://cryptovault-1-8zjm.onrender.com/)
  
  <br />
</div>

---

## :zap: Overview

**CryptoVault** (internally *Smart Crypto Tracker*) is a sleek, real-time cryptocurrency dashboard designed to help users track market trends, monitor coin performance, and manage a personalized watchlist.

Built with **React** and **Vite**, the application features a "dark-first" UI optimized for readability and performance. It utilizes **IndexedDB** for robust local state management, ensuring your watchlist remains persistent even without an account.

## :sparkles: Key Features

* **:chart_with_upwards_trend: Real-Time Market Data**: Live tracking of cryptocurrency prices, market caps, and volume.
* **:heart: Personalized Watchlist**: Add your favorite coins to a local watchlist (powered by `idb` for persistent local storage).
* **:art: Modern Dark UI**: A carefully crafted dark mode interface with custom accent colors (`#5B8DEF`, `#8B7FF4`) and the **Inter** typeface.
* **:zap: Smooth Animations**: Fluid page transitions and micro-interactions powered by **Framer Motion**.
* **:mobile_phone: Fully Responsive**: Optimized for desktop, tablet, and mobile devices using **Tailwind CSS**.
* **:bell: Instant Feedback**: Interactive toast notifications via `react-hot-toast`.

## :tools: Tech Stack

| Domain | Technologies |
| :--- | :--- |
| **Core Framework** | React 18, React DOM |
| **Build Tool** | Vite 5 |
| **Styling** | Tailwind CSS 3, PostCSS, Autoprefixer |
| **State/Storage** | IDB (IndexedDB Wrapper) |
| **Animation** | Framer Motion |
| **Icons** | Lucide React |
| **Routing** | React Router DOM |

## :rocket: Getting Started

Follow these steps to set up the project locally on your machine.

### Prerequisites

* Node.js (v16 or higher)
* npm or yarn

### Installation

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/cozyyuukii/cryptovault.git](https://github.com/cozyyuukii/cryptovault.git)
    cd cryptovault
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

3.  **Start the development server**
    ```bash
    npm run dev
    ```

4.  **Open in Browser**
    Visit `http://localhost:5173` to view the app.

## :open_file_folder: Project Structure

```text
src/
├── components/     # Reusable UI components
├── pages/          # Route views (Dashboard, Details, Watchlist)
├── services/       # API integration logic
├── utils/          # Helper functions and formatters
├── App.jsx         # Main application root
└── main.jsx        # Entry point

```

## :art: Customization

The project uses a centralized color palette defined in `tailwind.config.js`. You can modify the accent colors here:

```javascript
// tailwind.config.js
colors: {
  accent: {
    blue: '#5B8DEF',
    purple: '#8B7FF4',
    green: '#00D084',
    // ...
  }
}

```

## :page_facing_up: License

This project is open source and available under the [MIT License](https://www.google.com/search?q=LICENSE).

---

<div align="center">
<sub>Built with :blue_heart: by <a href="https://www.google.com/search?q=https://github.com/your-username">Your Yuukii</a></sub>
</div>

```

```
