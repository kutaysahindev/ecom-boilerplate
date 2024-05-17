# E-Commerce Boilerplate

A modular e-commerce boilerplate built with cutting-edge technologies: Next.js, Prisma, Stripe, and Tailwind CSS. This project provides a scalable foundation for creating modern e-commerce applications.

## Features

- **Next.js**: Fast and SEO-friendly React framework with SSR and SSG capabilities.
- **Prisma**: Next-generation ORM for seamless database interactions.
- **Stripe**: Integrated payment processing for secure and efficient transactions.
- **Tailwind CSS**: Utility-first CSS framework for rapid UI development.

## Getting Started

### Prerequisites

- Node.js (v14.x or later)
- PostgreSQL (or another supported database)
- Stripe account

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/e-commerce-boilerplate.git
   cd e-commerce-boilerplate
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up environment variables:**
   Create a `.env` file in the root directory and add the following:
   ```env
   DATABASE_URL=your_database_url
   NEXT_PUBLIC_STRIPE_PUBLIC_KEY=your_stripe_public_key
   STRIPE_SECRET_KEY=your_stripe_secret_key
   ```

4. **Run database migrations:**
   ```bash
   npx prisma migrate dev --name init
   ```

### Running the Application

1. **Development:**
   ```bash
   npm run dev
   ```
   Access the development server at `http://localhost:3000`.

2. **Production:**
   ```bash
   npm run build
   npm start
   ```

### Project Structure

- `pages/`: Next.js pages and API routes.
- `components/`: Reusable React components.
- `lib/`: Utility functions and configurations.
- `prisma/`: Prisma schema and migrations.
- `styles/`: Global and component-specific styles.


## License

This project is licensed under the MIT License.

---
