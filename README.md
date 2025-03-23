# Gourmet Delights - Virtual Hotel Menu

A modern, interactive virtual menu system for hotels and restaurants built with React, Express, and TypeScript.

## Features

- Interactive menu browsing
- Real-time updates
- Responsive design
- User authentication
- Admin dashboard for menu management
- Beautiful UI with Tailwind CSS

## Tech Stack

- Frontend: React, TypeScript, Tailwind CSS
- Backend: Express.js, TypeScript
- Database: PostgreSQL (Neon)
- ORM: Drizzle
- Authentication: Passport.js
- State Management: React Query

## Prerequisites

- Node.js (v18 or higher)
- PostgreSQL database
- npm or yarn

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/yourusername/gourmet-delights.git
cd gourmet-delights
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables:
```bash
cp .env.example .env
```
Edit the `.env` file with your configuration.

4. Set up the database:
```bash
npm run db:push
```

5. Start the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:5000`

## Deployment

This project is configured for deployment on Render. To deploy:

1. Push your code to GitHub
2. Connect your repository to Render
3. Set up the following environment variables in Render:
   - `DATABASE_URL`
   - `SESSION_SECRET`
   - `NODE_ENV=production`

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 