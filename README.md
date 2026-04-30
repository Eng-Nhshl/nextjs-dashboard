# Next.js Financial Dashboard

A full-stack financial dashboard built with the Next.js App Router.

**🌐 Live Demo:** [https://nextjs-dashboard-rosy-nine-40.vercel.app/](https://nextjs-dashboard-rosy-nine-40.vercel.app/)

### 🔑 Demo Credentials

- **Email:** `user@nextmail.com`
- **Password:** `123456`

## 🚀 Features

- **Authentication**: Secure login using Auth.js (NextAuth v5) and Middleware.
- **Dashboard**: Overview of revenue, latest invoices, and total statistics.
- **Invoices**: Full CRUD (Create, Read, Update, Delete) functionality with Server Actions.
- **Customers**: Searchable customer list with calculated totals.
- **Optimized Performance**: Implementation of Streaming with Suspense and PPR (Partial Prerendering).
- **Search & Pagination**: URL-based state management for shared search results.

## 🛠️ Tech Stack

- **Framework**: [Next.js 15](https://nextjs.org)
- **Database**: [Vercel Postgres](https://vercel.com) (Neon)
- **Auth**: [Auth.js](https://authjs.dev)
- **Styling**: [Tailwind CSS](https://tailwindcss.com)
- **Validation**: [Zod](https://zod.dev)
- **Icons**: [Heroicons](https://heroicons.com)

## ⚙️ Setup

1. **Clone the repo:**

   ```bash
   git clone <https://github.com/Eng-Nhshl/nextjs-dashboard.git>
   ```

2. **Install dependencies:**

   ```bash
   pnpm install
   ```

3. **Set up environment variables:**
   Create a `.env` file with your `POSTGRES_URL` and `AUTH_SECRET`.

4. **Seed the database:**

   ```bash
   pnpm run seed
   ```

5. **Run the app:**
   ```bash
   pnpm dev
   ```
