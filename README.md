# ZeroWaste Farm
A platform that connects farmers with buyers to reduce food waste.
---
## Table of Contents
- [About the Project](#about-the-project)
- [Project Overview](#project-overview)
- [Key Features](#key-features)
- [Tech Stack](#tech-stack)
- [Dependencies](#dependencies)
- [Installation & Setup](#installation--setup)
- [Folder Structure](#folder-structure)
- [Contributions](#contributions)
- [How to Contribute](#how-to-contribute)
- [Contact](#contact)
---
## About the Project
ZeroWaste Farm is a web application that helps farmers post surplus produce and buyers (restaurants, grocery stores, street vendors) find fresh, affordable food while reducing food waste. The platform provides real‑time listings, notifications, and a simple communication channel via WhatsApp.
---
## Project Overview
- **Goal**: Connect farmers and buyers to sell surplus produce before it goes to waste.
- **Impact**: Over 2,400 farmers registered, 18 000 kg of food saved monthly, and 94 % of listings sold within 3 days.
- **Architecture**: Full‑stack Next.js 16 with TypeScript, Prisma + PostgreSQL, and a modern UI built with Tailwind CSS and shadcn‑ui.
---
## Key Features
- **Farmers Post Surplus** – Register, upload photos, set quantity, price, and urgency.
- **Buyers Get Alerts** – Real‑time listings and push notifications.
- **Connect & Transact** – Direct WhatsApp contact, transaction tracking, and commission calculation.
- **Dashboard & API** – Admin dashboard for listings, users, and analytics.
- **Auth & Roles** – Secure authentication with NextAuth and role‑based access.
---
## Tech Stack
**Frontend:** Next.js 16, React 19, TypeScript, Tailwind CSS, shadcn‑ui, lucide‑react, class‑variance‑authority, tailwind‑merge, tw‑animate‑css, sonner, zustand.
**Backend:** Node.js, Prisma ORM, PostgreSQL, NextAuth, bcryptjs.
**Tools:** Git, VS Code, Docker (optional), Prisma CLI, tsx.
---
## Dependencies
```json
{
  "@base-ui/react": "^1.2.0",
  "@hookform/resolvers": "^5.2.2",
  "@prisma/adapter-pg": "^7.4.2",
  "@prisma/client": "^7.4.2",
  "@types/react-dropzone": "^4.2.2",
  "bcryptjs": "^3.0.3",
  "class-variance-authority": "^0.7.1",
  "cloudinary": "^2.9.0",
  "clsx": "^2.1.1",
  "lucide-react": "^0.577.0",
  "next": "16.1.6",
  "next-auth": "^5.0.0-beta.30",
  "next-themes": "^0.4.6",
  "react": "19.2.3",
  "react-dom": "19.2.3",
  "react-dropzone": "^15.0.0",
  "react-hook-form": "^7.71.2",
  "shadcn": "^4.0.0",
  "sonner": "^2.0.7",
  "tailwind-merge": "^3.5.0",
  "tw-animate-css": "^1.4.0",
  "zod": "^4.3.6",
  "zustand": "^5.0.11"
}
```
---
## Installation & Setup
1. **Clone the repo**
   ```bash
   git clone https://github.com/your-org/zerowaste-farm
   cd zerowaste-farm
   ```
2. **Install dependencies**
   ```bash
   npm install
   ```
3. **Set up environment variables** – create a `.env.local` file in the root:
   ```env
   DATABASE_URL=postgresql://user:pass@localhost:5432/zerowaste
   NEXTAUTH_SECRET=your_nextauth_secret
   ```
4. **Run database migrations and seed data**
   ```bash
   npx prisma migrate dev
   npx prisma db seed
   ```
5. **Start the development server**
   ```bash
   npm run dev
   ```
   The app will be available at `http://localhost:3000`.
---
## Folder Structure
```
zerowaste-farm/
├─ app/                 # Next.js app routes and layout
├─ components/          # Reusable UI components
├─ lib/                  # Services, Prisma client, utilities
├─ prisma/               # Prisma schema and migrations
├─ public/                # Static assets
├─ src/                   # Source files (auth, proxy, store, types)
├─ store/                 # Zustand stores
├─ types/                 # TypeScript type definitions
├─ package.json
└─ README.md
```
---
## Contributions
| Name | Role | Contributions |
|------|------|--------------|
| G.M Asif Foisal | Developer | Design Full System, Implementation |
---
## How to Contribute
1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/awesome-feature`.
3. Commit your changes with a clear message.
4. Push and open a Pull Request.
---
## Contact
**Live URL:** [Zero Waste Live Site](https://zerowaste-three.vercel.app)
**Email:** [asiffoisalaisc@email.com](mailto:asiffoisalaisc@email.com)  
**Portfolio:** [GitHub Profile](https://github.com/AsifFoisal)
