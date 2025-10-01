# Wally - Bitcoin Wallet Generator

A secure Bitcoin wallet generator application built with Next.js, providing safe generation and management of Bitcoin wallet addresses and private keys.

## Features

- 🔐 Secure Bitcoin wallet generation
- 📱 Responsive design for mobile and desktop
- 🎨 Modern UI with clean interface
- ⚡ Fast wallet generation
- 🔒 Private key security features
- 📋 Copy-to-clipboard functionality

## Tech Stack

- **Next.js** - React framework with App Router
- **TypeScript** - Type-safe development
- **Tailwind CSS** - Modern styling framework
- **Bitcoin Libraries** - Cryptographic wallet generation
- **React Hook Form** - Form handling

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn or pnpm

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd wally
```

2. Install dependencies:
```bash
pnpm install
# or
npm install
# or
yarn install
```

3. Start the development server:
```bash
pnpm run dev
# or
npm run dev
# or
yarn dev
```

4. Open your browser and navigate to `http://localhost:3000`

## Backend Integration

This frontend application works with a backend API for wallet generation. Ensure you have the backend server running for full functionality.

## Security Notes

- Private keys are generated client-side for security
- Never store private keys in plain text
- Always backup your wallet information securely
- This is for educational/demonstration purposes

## Building for Production

```bash
pnpm run build
# or
npm run build
# or
yarn build
```

## Deployment

The application can be deployed to Vercel, Netlify, or any other hosting platform that supports Next.js applications.

## License

MIT License
