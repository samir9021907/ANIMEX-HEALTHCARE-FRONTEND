# ANIMEX ANIMAL HEALTH CARE - FRONTEND

Modern React + Vite + Tailwind CSS frontend application for Animex Animal Health Care Pvt. Ltd.

## Features
- Complete Animal Health & Nutrition platform UI
- Products catalogue with multi-attribute filtering
- Clinical disease-to-solution directory
- Dealer locator with Indian states & districts
- CMS Admin Panel
- Fully responsive design

## Setup & Run Locally
```bash
# Install dependencies
npm install

# Start development server
npm run dev
```

## Environment Variables
Create a `.env` file (or set in Render/Vercel):
```env
VITE_API_URL="https://your-backend-app.onrender.com/api"
```

## Deployment on Render
1. Create a **Static Site** on Render.
2. Connect this repository.
3. Build Command: `npm run build`
4. Publish Directory: `dist`
5. Add Environment Variable: `VITE_API_URL` pointing to your deployed backend.
