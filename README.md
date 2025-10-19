# Momentum (777)

> Empower individuals to build life-changing habits through intelligent, personalized tracking

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)](https://github.com/momentum/tracker)

## Overview

Momentum is a comprehensive habit tracking platform designed to help users consistently achieve personal and professional goals. By leveraging AI and behavioral science, we provide intelligent insights and personalized guidance to transform habit formation.

## Features

- ✨ AI-powered habit tracking and recommendations
- 🚀 Personalized goal setting and progress visualization
- 💡 Comprehensive behavioral insights
- 🔒 Secure, privacy-focused user authentication

## Tech Stack

**Frontend:**
- React 18
- TypeScript
- Tailwind CSS
- Zustand
- React Router
- TanStack Query

**Backend:**
- Next.js API Routes
- Node.js 20 LTS
- PostgreSQL with Prisma ORM
- NextAuth.js

**Deployment:**
- Vercel
- Railway
- Supabase

## Quick Start

### Prerequisites

```bash
node >= 18.0.0
npm >= 9.0.0
```

### Installation

```bash
# Clone the repository
git clone https://github.com/momentum/tracker.git

# Install dependencies
cd tracker
npm install

# Set up environment variables
cp .env.example .env
# Edit .env with your configuration

# Run development server
npm run dev
```

Visit `http://localhost:3000` to see the application.

## Project Structure

```
/
├── src/
│   ├── components/     # React components
│   ├── pages/          # Next.js pages
│   ├── utils/          # Utility functions
│   └── styles/         # Tailwind CSS
├── prisma/             # Database schema
├── public/             # Static assets
└── tests/              # Test files
```

## Development

### Available Scripts

```bash
npm run dev         # Start development server
npm run build       # Build for production
npm run test        # Run tests
npm run lint        # Lint code
```

### Environment Variables

Required environment variables:

```env
DATABASE_URL=postgresql://username:password@localhost:5432/momentum
NEXTAUTH_SECRET=your_nextauth_secret
```

## Testing

```bash
# Run unit tests
npm run test

# Run with coverage
npm run test:coverage
```

## Deployment

### Vercel (Recommended)

```bash
npm run build
vercel --prod
```

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

For support, email support@momentum.dev or open an issue.

---

**Built with ❤️ for Personal Growth**