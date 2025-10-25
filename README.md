# sunsethosting
1. Clone the repo (or copy files into two folders: `frontend` and `backend`).
2. Setup backend environment variables (see `backend/.env.example`).
3. Start MongoDB (local or Atlas) and populate .env.
4. Install & run backend: `cd backend && npm install && npm run dev`.
5. Install & run frontend: `cd frontend && npm install && npm run dev`.
6. For deployment on Hostingr: upload backend to a Node-capable app (they support Node apps), and set environment variables. Serve frontend as static or use Vercel/Netlify and point domain to Hostingr nameservers or add CNAME.
