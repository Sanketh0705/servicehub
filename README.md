# ServiceHub – Local Services Marketplace

ServiceHub is a frontend-first business-value MVP for discovering, comparing, saving and booking trusted local service professionals.

## Features
- Search and category filters
- Service cards with ratings, pricing and trust signals
- Save/favorite services
- Booking flow with date, time and address
- Customer dashboard and booking status
- Responsive design
- LocalStorage persistence
- AI-assisted smart matching concept

## Stack
React, Vite, JavaScript, CSS, Lucide React, GitHub Actions and Vercel.

## Run
```bash
npm install
npm run dev
```

## Production build
```bash
npm run build
```

## CI/CD
`.github/workflows/ci.yml` installs dependencies and verifies the production build on pushes and pull requests to `main`. Connect the GitHub repository to Vercel for production deployment.

## AI usage
AI tools were used for product ideation, implementation assistance, debugging, CI/CD guidance and documentation. The final implementation was reviewed and tested as part of development.

## Business value
ServiceHub reduces the friction of finding reliable local professionals by combining discovery, trust signals, transparent starting prices and booking in one interface.

## Future scope
Authentication, REST API, PostgreSQL, provider onboarding, payments, real-time availability, maps, admin moderation and a production AI recommendation model.
