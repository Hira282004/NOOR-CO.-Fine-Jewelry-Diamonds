# Free Deployment & Domain Guide - NOOR & CO. Luxury Jewelry

Your full-stack website (React Frontend + Node.js Express Backend API + Data Persistence) is pre-configured for **100% Free Hosting** with a **Free Domain** and **Database**.

---

## 🌟 Option 1: Deploy on Render.com (Recommended - 100% Free Full-Stack + Database)

Render provides free hosting for Node.js apps + React frontends + free PostgreSQL database with a free `.onrender.com` SSL domain.

### Steps to Launch:
1. Create a free account at [render.com](https://render.com).
2. Push your project folder to **GitHub** or **GitLab**.
3. In Render Dashboard, click **New +** -> **Web Service**.
4. Connect your GitHub repository.
5. Set the following settings:
   - **Environment**: `Node`
   - **Build Command**: `npm run build && cd backend && npm install`
   - **Start Command**: `node backend/server.js`
6. Click **Create Web Service**.
7. 🎉 Your website is now **LIVE** on a free domain like `https://noor-jewelry-store.onrender.com`!

---

## ⚡ Option 2: Deploy on Vercel (1-Click Deployment - Free `.vercel.app` Domain)

Vercel offers global CDN hosting with automatic SSL certificates and free `.vercel.app` custom domains.

### Steps to Launch:
1. Create a free account at [vercel.com](https://vercel.com).
2. Install Vercel CLI or connect your GitHub repository:
   ```bash
   npx vercel
   ```
3. Vercel will automatically detect `vercel.json` and deploy your website in 30 seconds.
4. 🎉 Your website is **LIVE** at `https://noor-jewelry-store.vercel.app`!

---

## 🗄️ Database Options (100% Free Cloud DBs)
- **Built-in Persistent JSON Vault**: Pre-configured in `backend/data/` (`products.json`, `inquiries.json`, `orders.json`).
- **Free Cloud PostgreSQL**: Create a free Postgres database on [Render.com](https://render.com) or [Neon.tech](https://neon.tech) and paste the database URL.
- **Free MongoDB Atlas**: Create a free cluster on [mongodb.com/atlas](https://www.mongodb.com/cloud/atlas).
