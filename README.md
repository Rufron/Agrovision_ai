# 🌾 AgroVision — AI Agricultural Insights

Web app providing ML-based crop predictions, weather forecasts, and AI-generated farming insights.
Built with Vite + React + TypeScript + Supabase.

Live: [agrovision-2.vercel.app](https://agrovision-2.vercel.app/)

Overview (Canva): https://www.canva.com/design/DAG1ar8opDo/1MrMNsOWD2ZOLpB_9igLRg/edit

## 📷 Demo / Screenshots

![Screenshot](./image.png)

## 🗂 Project Structure
``` bash
agrovision_ai/
├── backend/      # ML/Backend service
├── public/       # Static assets
├── src/          # Frontend (React + Vite)
├── supabase/     # Supabase functions
├── .env          # Environment variables
├── .gitignore
├── README.md
├── SETUP_DASHBOARD_TABLES.sql
├── index.html
├── package.json
├── vite.config.ts
├── tailwind.config.ts
└── tsconfig.*.json
```

## 🚀 Features

- Predictive Analysis: Upload data → ML predictions

- Weather Forecasts: 5-day real-time updates

- AI Insights: Actionable recommendations via Supabase Edge

- Fast UI: Vite + React + Tailwind + ShadCN

- Responsive: Desktop & mobile

- Secure: API keys in .env

## 🛠 Setup
1. Prerequisites
``` bash

Node.js v18+

npm or yarn

Supabase project

Hugging Face API key

OpenWeather API key
```

2. Install
``` bash
git clone https://github.com/Rufron/agrovision_ai.git
cd agrovision_ai
npm install
or
yarn install

```
3. Environment

Create .env in root:
``` bash

VITE_API_BASE_URL="YOUR_ML_BASE_URL"
NEXT_PUBLIC_WEATHER_API_KEY="YOUR_OPENWEATHER_API_KEY"
VITE_HF_API_KEY="YOUR_HUGGING_FACE_API_KEY"
VITE_SUPABASE_URL="https://YOUR_SUPABASE_URL.supabase.co"
VITE_SUPABASE_PUBLISHABLE_KEY="YOUR_SUPABASE_KEY"
```


Ensure .env is in .gitignore

4. Run Locally
``` bash
npm run dev
or
yarn dev
```
then
``` bash

Open http://localhost:3000
```

## ⚙️ Usage

Prediction: Upload data → ML analysis

Weather: Check forecasts

Insights: Generate AI recommendations

Dashboard: View predictions, insights, and forecasts

## 🧭 Future Roadmap 

1. Improve ML accuracy


2. Multi-language support

3. Better UI (charts, export, animations)

4. Offline PWA mode

## 👥 Contributors
Name	Role
1. Brian Kipchumba - Frontend & Ai integration.
2. Faith Kiplagat - Backend & DB.
3. Borchar Gatwetch	- Frontend & Machine Learning.