# 🌱 GoTouchGrass Pro  
### *AI-powered Roast & Outdoor Accountability System*  

> “A full-stack reality check that literally makes you touch grass.”  

<p align="center">
  <img src="https://img.shields.io/badge/AI-Gemini%202.5%20Flash-34A853?logo=google" />
  <img src="https://img.shields.io/badge/Frontend-Next.js%20%2B%20Tailwind-blue?logo=nextdotjs" />
  <img src="https://img.shields.io/badge/Backend-Node.js%20%2B%20Express-green?logo=nodedotjs" />
  <img src="https://img.shields.io/badge/License-MIT-yellow" />
</p>

---

## 🚀 Overview  

**GoTouchGrass Pro** is a funny yet functional app that uses **Google Gemini 2.5 Flash** to verify whether you’ve actually *touched grass* 🌿.  

Upload a photo → Gemini analyzes it → you either get praised for going outdoors or roasted for staying inside.  

It also sends **reminders, pings, and notifications** if you go too long without verifying your outdoor adventures — because accountability is key.  

---

## ✨ Features  

- **🌱 Outdoor Verification** – Upload a photo; Gemini AI checks if it’s truly outdoors.  
- **🔥 AI Roast Engine** – Get roasted if your image screams “basement dweller.”  
- **📍 Smart Location Suggestions** – Gemini suggests fun outdoor activities nearby.  
- **📧 Pings & Notifications** – Reminds (or publicly shames) you when you don’t touch grass.  
- **🎨 Dynamic Gradient Themes** – Change between 4 soothing color modes (green → red).  
- **🔔 Browser Notifications** – Subtle nudges to step away from your desk.  
- **📊 User Streak Tracker** – Keep tabs on how often you’ve been outdoors.  

---

## 🧩 Tech Stack  

| Layer | Technologies Used |
|-------|-------------------|
| **Frontend** | Next.js, React, TailwindCSS, Lucide Icons |
| **Backend** | Node.js + Express |
| **AI** | Google **Gemini 2.5 Flash** |
| **Database** | Auto-configured SQLite / local JSON |
| **Email / Notifs** | SendGrid (optional) + Browser Notifications |
| **Geo / Suggestions** | OpenStreetMap + Gemini reasoning |

---

## 🧠 How It Works  

1. Upload a photo of yourself (preferably outside).  
2. The backend sends it to **Gemini 2.5 Flash** for content verification.  
3. Gemini analyzes lighting, background, and environmental context.  
4. If you’re outdoors → you’re praised for touching grass.  
5. If not → Gemini roasts you harder than a Reddit comment section.  
6. If you stay indoors too long → GoTouchGrass pings you (and possibly your friends).  

---

## 🖼️ Screenshots  

<p align="center">
  <img src="docs/screenshot_home.png" width="80%" alt="Home Page Preview" />
  <br/><em>🏡 Home screen – Upload your 'proof of grass' here.</em>
</p>

<p align="center">
  <img src="docs/screenshot_roast.png" width="80%" alt="Roast Result Example" />
  <br/><em>🔥 AI roast results – brutally honest outdoor diagnostics.</em>
</p>

<p align="center">
  <img src="docs/screenshot_theme.png" width="80%" alt="Theme Selector" />
  <br/><em>🎨 Switch between dynamic nature-inspired color themes.</em>
</p>

<p align="center">
  <img src="docs/screenshot_notify.png" width="80%" alt="Notification System" />
  <br/><em>🔔 Smart reminders and pings to get you moving outdoors.</em>
</p>

---

## ⚙️ Setup  

### 🧾 Prerequisites  
- Node.js 18+  
- Gemini API key (add to `.env` file)  
- Optional: SendGrid key for email notifications  

### 🛠 Installation  

```bash
# Clone the repo
git clone https://github.com/yourusername/go-touch-grass-pro.git
cd go-touch-grass-pro

# Install dependencies
npm install

# Start backend
cd backend
npm start

# Start frontend
cd ../frontend
npm run dev
# 🌱 GoTouchGrass Pro

The ultimate roast-powered outdoor accountability coach. Prove you went outside, get hilarious AI roasts if you didn’t, and track your grass-touching streaks.

---

## 🛠 Installation

### Clone the repo
```bash
git clone https://github.com/yourusername/go-touch-grass-pro.git
cd go-touch-grass-pro
```

### Install dependencies
```bash
npm install
```

### Start backend
```bash
cd backend
npm start
```

### Start frontend
```bash
cd ../frontend
npm run dev
```

Then visit 👉 [http://localhost:3000](http://localhost:3000)

---

## 📸 Example Output

**✅ Verified:**  
> “Yo, you actually touched grass! Nice job! Real sunlight, real vibes, no RGB needed.”

**❌ Not Verified:**  
> “This lighting screams 4K monitor, not sunshine. Go touch some actual photons.”

---

## 🔔 Notifications

- Local browser reminders when you’re overdue for a grass session.  
- Optional email pings using SendGrid (“Subject: Still indoors? 😬”).  
- Weekly summaries of your outdoor streaks.

---

## 🧪 Future Additions

- 🪩 Friend leaderboards  
- 🌎 “Grass Map” of verified outdoor spots  
- 🧭 Challenge mode (“Find a tree and prove it”)  
- 🗣 Voice notifications: “Bro, go outside.”

---

## 📷 Screenshots

![Dashboard Placeholder](./screenshots/dashboard.png)  
*Example dashboard with streaks, verification, and roasts.*

![Verification Placeholder](./screenshots/verification.png)  
*Upload a photo to verify you actually touched grass.*

![Settings Placeholder](./screenshots/settings.png)  
*Manage your reminders, contacts, and notifications.*

