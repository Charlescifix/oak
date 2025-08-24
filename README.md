# AegoLink - AI-Powered Crypto Wealth Engine

A modern, responsive landing page for AegoLink's AI-driven cryptocurrency wealth management platform.

## Features

- 🤖 **AI-Powered Trading**: Autonomous agents with real-time ML signals
- 💎 **Glassmorphism Design**: Modern UI with glass effects and smooth animations
- 📱 **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- 🔒 **Security-Focused**: Bank-grade security with on-chain transparency
- 🚀 **Token Launch**: Integration with Bitcoin-pegged AegoLink Token

## Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **Styling**: Tailwind CSS (CDN)
- **Icons**: Lucide React
- **Charts**: Chart.js
- **Backend**: Node.js with Express.js
- **Deployment**: Railway

## Local Development

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm start
```

3. Open your browser and navigate to:
```
http://localhost:3000
```

## Railway Deployment

This project is configured for automatic deployment on Railway:

1. Connect your GitHub repository to Railway
2. Railway will automatically detect the Node.js project
3. The app will be built and deployed using the configuration in `railway.json`

### Environment Variables

No environment variables are required for basic deployment.

## Project Structure

```
oak_fund/
├── index.html              # Main landing page
├── server.js               # Express.js server
├── package.json            # Node.js dependencies
├── railway.json            # Railway deployment config
├── Procfile               # Process file for deployment
├── .gitignore             # Git ignore rules
└── README.md              # This file
```

## Deployment Commands

- **Start**: `npm start`
- **Development**: `npm run dev`

## Features Overview

### Sections
- **Hero**: AI-powered wealth management introduction with interactive charts
- **Our Packages**: 9 feature cards showcasing platform capabilities
- **Fund Your Future**: Crypto deposit form with trust indicators
- **AegoLink Token**: Token launch information and early access signup
- **Footer**: Links and copyright information

### Responsive Design
- Mobile-first approach with Tailwind CSS breakpoints
- Optimized typography scaling (text-3xl → lg:text-6xl)
- Adaptive layouts (1 column → 2 columns → 3 columns)
- Touch-friendly interactive elements

## License

MIT License - see LICENSE file for details.