# Crypto Tracker

Crypto Tracker is a React + Vite application for exploring live cryptocurrency market data. It pulls data from the CoinGecko API and lets users browse popular coins, search by name or symbol, sort by price or market cap, and open detailed coin pages with price charts.

## Features

- Browse a live list of cryptocurrencies
- Search coins by name or ticker symbol
- Sort by rank, price, 24h change, or market cap
- View detailed coin information and a 7-day price chart
- Responsive UI built with React and Recharts

## Tech Stack

- React
- Vite
- React Router
- Recharts
- CoinGecko API

## Getting Started

### Prerequisites

- Node.js 18+ recommended
- npm or pnpm

### Installation

```bash
npm install
```

### Run locally

```bash
npm run dev
```

The app will be available at http://localhost:5173 by default.

### Build for production

```bash
npm run build
```

## Project Structure

- src/pages - Home and coin detail views
- src/components - Reusable UI components
- src/api - API integration with CoinGecko
- src/utils - Formatting helpers

## License

This project is for educational and personal use.
