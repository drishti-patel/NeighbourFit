NeighbourFit — Smart Lifestyle Matcher

NeighbourFit is a full-stack web application that helps users discover Indian localities that align with their lifestyle preferences. Whether you're seeking a safe environment, vibrant culture, or remote-work-ready zones, NeighbourFit offers curated suggestions based on your priorities.

---

## Key Highlights

- ⚛️ **Frontend**: Built using React (Vite)
- 🛠️ **Backend**: Node.js + Express server
- ⚡ **Live Suggestions**: Area recommendations update dynamically based on user inputs
- 🖼️ **Visual Layout**: Clean UI with cards and images to display neighborhood insights
- 🧩 **Zero Database Setup**: All data served from static JSON (simple and fast)

---

## Local Setup Guide

To run the app locally on your machine:

## Backend Server (Runs on Port `4000`)

```bash
cd backend
npm install
npm start
🔹 Frontend App (Runs on Port 5173)
bash
Copy
Edit
cd frontend
npm install
npm run dev
👉 Visit the frontend at: http://localhost:4000

📮 API Overview
POST /api/recommend

Sends the user’s preferences to receive a list of suitable neighborhoods.

🔸 Request Example:
json
Copy
Edit
{
  "workFromHomeFriendly": true,
  "minAffordability": 5,
  "minSafety": 6,
  "minCulture": 7,
  "minWalkability": 7
}
Author
Drishti Patel
