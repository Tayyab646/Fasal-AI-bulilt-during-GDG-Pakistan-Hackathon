# 🌾 Fasal AI — فصل اے آئی

> AI-powered smart farming assistant for Pakistani farmers — available in English & Urdu

Built at the **AI Seekho Hackathon** organized by **GDG Pakistan** 🇵🇰

---

## 🔴 Problem Statement

Pakistan is an agricultural country where millions of farmers in remote areas face these challenges daily:

- ❌ Cannot identify crop diseases until it is too late
- ❌ No access to agricultural experts in rural areas
- ❌ No weather forecasting tools for farm planning
- ❌ Most farming apps are in English only — language is a barrier
- ❌ Financial decisions made blindly without market information

**Fasal AI solves all of this — for free.**

---

## 💡 Solution

Fasal AI puts an AI-powered agricultural expert in every farmer's pocket. Farmers can chat in **Urdu or English**, scan crop photos for disease detection, check live weather, and make smarter financial decisions — all from one app.

---

## ✨ Features

| Feature | Description |
|---|---|
| 📷 **Crop Disease Detection** | Upload a crop photo and get instant AI diagnosis with treatment advice |
| 💬 **AI Farming Advisor** | Chat in Urdu or English and get expert farming answers 24/7 |
| 🌤️ **Live Weather** | Real-time weather forecasts based on your farm location |
| 🗺️ **Farm Map** | Mark and track your farm location on an interactive map |
| 📔 **Farmer's Journal** | Record crop progress, treatments, and observations over time |
| 📊 **Market Rates & Calculator** | Check crop prices and calculate profits before selling |

---

## 🛠️ Tech Stack

- **Frontend:** React + Vite + TailwindCSS
- **Backend:** Node.js + Express + TypeScript
- **AI:** Google Gemini API (text + vision)
- **Deployment:** Google Cloud Run
- **Language Support:** English + اردو

---

## 🚀 Getting Started

### Prerequisites

- Node.js v18 or higher → [Download here](https://nodejs.org/)
- A free Gemini API key → [Get it here](https://aistudio.google.com/apikey)

### Installation

**1. Clone the repository**
```bash
git clone https://github.com/your-username/fasal-ai.git
cd fasal-ai
```

**2. Install dependencies**
```bash
npm install
```

**3. Set up your API key**

Create a `.env` file in the root folder:
```
GEMINI_API_KEY=AIzaSy_your_key_here
APP_URL=http://localhost:3000
```

**4. Start the app**
```bash
npm run dev
```

**5. Open in browser**
```
http://localhost:3000
```

---

## 📁 Project Structure

```
fasal-ai/
├── index.html          ← Main app UI (all screens & logic)
├── server.ts           ← Express server + Gemini AI proxy
├── package.json        ← Project config & scripts
├── .env                ← Your API key (never share this!)
├── .env.example        ← Template for .env file
├── vite.config.ts      ← Frontend build config
├── tsconfig.json       ← TypeScript config
└── src/
    ├── App.tsx         ← React entry point
    └── main.tsx        ← React root mount
```

---

## 🌍 Why Fasal AI?

Technology should not only exist for people who speak English and live in cities. Fasal AI is built for the farmer in Punjab who speaks Urdu, for the farmer in Sindh who loses crops to disease every year, and for the farmer in KPK who has no agricultural office nearby.

**If we can help even one farmer save his harvest — that is a family fed and Pakistan growing stronger. 🌱**

---

## ⚠️ Security Note

- Never share your `.env` file or upload it to GitHub
- The `.gitignore` already excludes `.env` automatically
- Always create a new API key if your old one was exposed

---

## 🤝 Built At

**AI Seekho Hackathon** by **GDG Pakistan**

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<p align="center">Made with ❤️ for Pakistani Farmers 🇵🇰</p>
