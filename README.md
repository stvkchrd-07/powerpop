# PowerPop

Stay Charged. Stay Ahead.

## Local Setup

1. npm install
2. cp .env.example .env
3. npx prisma generate
4. npx prisma migrate dev --name init
5. npm run dev

## Deploy to Vercel

1. Push to GitHub
2. Import repo in Vercel
3. Add Environment Variables (see .env.example)
4. Set build command: npm run build
5. Add Stripe webhook: /api/orders
