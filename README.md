# 🛍️ TradeCircle

**TradeCircle** is a peer-to-peer trading platform that empowers communities to exchange goods and services locally, fairly, and affordably. Designed specifically for low-income areas, TradeCircle enforces a $50 maximum trade limit and connects users only within a 10-mile radius — all while promoting economic education, gamification, and safe interactions.

> 🔥 Built for real-world use and the [INSERT HACKATHON NAME] Hackathon challenge.

---

## 🌍 Why TradeCircle?

Many communities face barriers to fair, local trade. TradeCircle solves this with:

- ✅ **No fees** – Always free for users.
- ✅ **Local-first trading** – Geolocation keeps trades within 10 miles.
- ✅ **Fair pricing** – Hard cap of $50 per trade.
- ✅ **Empowerment** – Budget help, side hustle ideas, and gamified financial literacy.
- ✅ **Moderation tools** – Live moderation and support for a safe environment.

---

## 🚀 Features

| Category | Feature |
|---------|---------|
| 🗺️ Location | Detects user’s location and restricts trades to a 10-mile radius |
| 💸 Pricing Cap | Rejects any trades over $50 |
| 🔍 Search & Filter | Browse trades by category, price, or proximity |
| 💬 Private Messaging | Real-time chat for trade coordination |
| 👥 Friends & Blocking | Add/remove friends, block/report users |
| ⭐ Reviews | Leave and view user testimonials |
| 📜 Rules & Policies | Built-in safety and community guidelines |
| 🛡️ Moderation | Admin tools to flag/remove harmful content or repeat offenders |
| 🧠 Education | Budgeting help, economic tips, and trade-based challenges |
| 🎮 Gamification | Daily missions, badges, and XP for community engagement |

---

## 🎯 Use Cases

- Trade gently used clothing, tools, or school supplies
- Offer babysitting or tutoring in exchange for other services
- Budget-friendly community bartering
- Promote economic resilience in under-resourced areas

---

## 🛠️ Tech Stack

| Area        | Tech |
|-------------|------|
| Frontend    | HTML, Tailwind CSS, JavaScript (Vanilla / Alpine.js) |
| Backend     | Firebase (Auth, Firestore, Functions) |
| Real-Time   | Firestore live updates (chat, trades) |
| Payments    | Stripe (test mode only) |
| Geolocation | HTML5 Geolocation API |
| Hosting     | Firebase Hosting (free forever) |
| Support     | EmailJS, Discord (for live tech support) |

---

## 📦 Installation (For Developers)

1. **Clone the repo**
   ```bash
   git clone https://github.com/kdsas/tradecircle.git
   cd tradecircle

Install Tailwind (optional for dev build)

bash
Copy
Edit
npm install
npx tailwindcss -i ./style.css -o ./dist/output.css --watch

Setup Firebase

Create a Firebase project at firebase.google.com

Enable Firestore and Authentication (email/password)

Paste your config into your JS files

Run locally
Just open index.html in your browser or use Live Server in VS Code.

🌐 Live Demo
🔗 https://kdsas.github.io/tradecircle


🤝 Contributing
Pull requests are welcome! If you have ideas for improving accessibility, gamification, or support for under-resourced communities, feel free to open an issue or PR.

📄 License
MIT License — free to use, adapt, and improve.

🙌 Acknowledgments
Built with Tailwind CSS

Powered by Firebase

Inspired by communities in need of fair and creative economic tools

💡 TradeCircle isn't just a trading app — it's a movement for economic justice and empowerment.
