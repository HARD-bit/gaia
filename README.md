# 🤖🛡️ Gaia – AI-Powered Women Safety Application

**Gaia** is a prototype **women safety web application** built with **Streamlit**, combining **AI-powered emotional support**, **emergency simulation**, and **geospatial awareness** to enhance personal safety.

The project integrates **large language models (via Groq)**, **interactive maps**, and **route calculation services** to demonstrate how technology can support safety-oriented digital solutions.

---

## 🎯 Project Purpose

* Provide **AI-based conversational support** in stressful or unsafe situations
* Simulate **emergency assistance** interactions
* Visualize **potentially dangerous areas** on an interactive map
* Calculate **safe routes** between locations
* Showcase a real-world **end-to-end Streamlit application**

---

## 🧩 Application Features

The app is organized into multiple sections accessible from the sidebar.

### 👤 Personal Information

* Collects basic user information (name, age, country, contact details)
* Data is used only within the session (no persistence)
* Acts as a user onboarding step

---

### 💬 AI-Powered Support (Gaia AI)

* Simulated conversation with an AI assistant
* Built using **Groq API** with the `llama3-8b-8192` model
* Maintains conversation context via Streamlit session state
* Designed for emotional support and guidance

---

### 🚨 Emergency Call Simulation

* Simulates contacting emergency services
* Provides immediate feedback and reassurance
* Demonstrates UX flow for emergency scenarios

---

### 🗺️ Dangerous Area Map (Prototype)

* Interactive world map using **Folium**
* Displays predefined areas with different danger levels
* Color-coded markers:

  * 🟥 High risk
  * 🟧 Medium risk
  * 🟩 Low risk
* Includes a **heatmap layer** for visual density

---

### 🚗 Route Calculator (OpenRouteService)

* Calculates driving routes between two geographic coordinates
* Integrates **OpenRouteService (ORS) API**
* Displays routes on an interactive map
* Useful for route awareness and navigation safety

---

## 🧠 Architecture Overview

* **Frontend**: Streamlit
* **AI Backend**: Groq LLM API
* **Maps & Visualization**: Folium
* **Routing API**: OpenRouteService
* **State Management**: Streamlit Session State

---

## 🐍 Technologies Used

* **Python 3**
* **Streamlit** – web application framework
* **Groq SDK** – LLM inference
* **Folium** – interactive maps
* **Pandas** – data handling
* **Requests** – API communication

---

## 📂 Project Structure

```
📦 gaia-women-safety-app
 ┣ 📜 app.py
 ┣ 📜 requirements.txt
 ┗ 📜 README.md
```

---

## 🔐 Security & Privacy Notes

⚠️ **Important (Prototype Disclaimer)**

* API keys are hardcoded for demonstration purposes only
* No user data is stored or transmitted externally (except API calls)
* Not intended for production use without proper security hardening

---

## 🚀 How to Run
This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.



## 🌱 Future Improvements

* Secure API key management (environment variables)
* Real-time emergency contact integration
* Real crime statistics data sources
* Safe-route scoring (lighting, crowd density, time of day)
* Mobile-first UI redesign

---

## 👤 Author

**Gabriele Rumi**
Computer Science Student | Data Engineering

---
