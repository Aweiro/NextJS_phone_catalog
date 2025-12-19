# Phone Catalog (Next.js)

A full-stack phone catalog application built with **Next.js**, **TypeScript**, and **PostgreSQL**.  
The project showcases modern React and Next.js practices, server-side rendering, database integration, and scalable frontend architecture.

## 🔗 Live Demo
https://phone-catalog-latest.onrender.com/cart?from=%2Ffavorites

---

## 🚀 Tech Stack

### Frontend
- **Next.js 16** (App Router)
- **React 19**
- **TypeScript**
- **Tailwind CSS**
- **SCSS / Sass**
- **classnames**

### State Management
- **Redux Toolkit**
- **React Redux**

### UI & UX
- **Swiper**
- **React Slick / Slick Carousel**
- **React Swipeable**

### Backend / Server
- **Next.js API Routes**
- **Prisma ORM**
- **PostgreSQL**
- **bcryptjs** (password hashing)

### Media & Assets
- **Cloudinary** (image storage and optimization)

### Database
- **PostgreSQL**
- **Prisma Client**
- Database seeding via custom `seed.ts`

### Tooling & Quality
- **ESLint**
- **Prettier**
- **TypeScript ESLint**
- **Husky** + **lint-staged**
- **dotenv**

### Deployment
- **Vercel** (recommended)
- **GitHub Pages** (static assets)

---

## ✨ Features

- Phone catalog with dynamic data
- Server-side rendering (SSR) and static generation
- Global state management with Redux Toolkit
- Responsive UI with Tailwind CSS and SCSS
- Image upload and optimization via Cloudinary
- Admin styles built with a separate Tailwind config
- Secure password hashing
- Typed database access with Prisma
- Pre-commit linting and formatting

---

## 🛠️ Getting Started

### Prerequisites
- Node.js ≥ 18
- PostgreSQL
- npm / yarn / pnpm

### Installation
```bash
git clone https://github.com/Aweiro/NextJS_phone_catalog.git
cd NextJS_phone_catalog
npm install
npx prisma migrate dev
npm run seed
npm run dev

🎯 Project Goal

This project was built as a portfolio / CV project to demonstrate:
	•	full-stack development with Next.js
	•	relational database work with PostgreSQL
	•	Prisma ORM and data modeling
	•	modern UI development with Tailwind
	•	scalable and maintainable project structure
