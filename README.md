# AK Todo List

**Fullstack app:** React + Vite + Tailwind + shadcn/ui (frontend)  
Node.js/Express + PostgreSQL (backend)

## Getting Started

### Backend

```bash
cd backend
cp .env.example .env
npm install
npm run dev
```

### Database

- Update `.env` with your PostgreSQL credentials.
- Run the SQL in `db/schema.sql`

### Frontend

```bash
cd frontend
npm install
npx shadcn-ui@latest init
npx shadcn-ui@latest add button input card
npm run dev
```

---

**Connect to your backend at `http://localhost:5000/api` (adjust as needed).**
