# Full Stack Content Management System | E-Commerce | Dashboard: Next.js App Router, React, Tailwind, Prisma, MySQL, Shadnc

Next.js App Router, React, Tailwind, Prisma, MySQL, shadcn/ui, Clerk, Stripe, Cloudinary

### Prerequisites

**Node version 14.x**

### Install packages

```shell
npm i
```

### Setup .env file

```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

DATABASE_URL=''

NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=""
STRIPE_API_KEY=
STRIPE_WEBHOOK_SECRET=
```

### Connect to DB and Push Prisma

```shell
npx prisma generate
npx prisma db push
```

### Install and start the app

```shell
npm install
npm run dev
```
