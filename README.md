# 🗄️ DB Quest — Database Normalization Learning App

> **An interactive, gamified web app for learning Database Normalization — built by [Learn With iKay](https://web.facebook.com/learnwithikay) and powered by [Claude.ai](https://claude.ai).**

---

<div align="center">

![Learn With iKay](https://img.shields.io/badge/Made%20by-Learn%20With%20iKay-0d4a2a?style=for-the-badge&logo=graduation-cap)
![Built With Claude](https://img.shields.io/badge/Built%20with-Claude.ai-cc7a00?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

</div>

---

## 📖 About This Project

**DB Quest** was created as a teaching resource after a weekend session where two kids — aged **11 and 13** — were introduced to core database concepts: Primary Keys, Foreign Keys, and the three Normal Forms (1NF, 2NF, 3NF).

The goal was simple: **make the lesson stick**.

Instead of a static worksheet, we described what we needed to Claude.ai in plain English — and it built a fully functional, branded, interactive learning game. No IDE. No terminal. No code editor. Just a conversation.

This project is a testament to two things:
1. **Learn With iKay's mission** — breaking down fundamental data skills for every mind, regardless of age or background.
2. **The power of Claude.ai** — turning ideas into working applications instantly.

---

## ✨ Features

### 4 Interactive Learning Modes

| Mode | Description |
|------|-------------|
| 📚 **Learn the Concepts** | 6 illustrated lessons with real table examples covering databases, PKs, FKs, 1NF, 2NF, and 3NF |
| 🧠 **Take the Quiz** | 10 randomised questions with instant feedback, explanations, and streak-based bonus points |
| 🔗 **Match-Up Game** | Click-to-match terms and definitions — great for vocabulary reinforcement |
| 🛠️ **Fix the Database!** | 3 progressive challenges where you click on broken cells and see the corrected table |

### Gamification
- ⭐ **Points system** — earn 10 pts per correct answer, with streak bonuses
- 🔥 **Streak tracker** — consecutive correct answers multiply your score
- 🎮 **Level progression** — level up every 100 points
- 🏆 **Results screen** — personalised feedback based on your score percentage

### Design & UX
- Clean **white-dominant** design with deep forest green brand accents
- Fully **responsive** — works on desktop, tablet, and mobile
- **Zero dependencies** — single HTML file, no npm, no build step, no server needed
- Smooth CSS animations and micro-interactions throughout
- Custom **Learn With iKay** branding with embedded logo

---

## 🚀 Getting Started

### Option 1 — Open Directly (Recommended)
This app is a **single self-contained HTML file**. No installation needed.

```bash
# Clone the repo
git clone https://github.com/TheIkechukwu/db-quest.git

# Open in your browser
open index.html
```

Or simply **download `index.html`** and double-click it.

### Option 2 — Serve Locally
```bash
# Python 3
python -m http.server 8000

# Then open http://localhost:8000/index.html
```

### Option 3 — Deploy to GitHub Pages
1. Fork this repository
2. Go to **Settings → Pages**
3. Set source to the `main` branch, root folder
4. Your app will be live at `https://<your-username>.github.io/db-quest/index.html`

---

## 🎓 What Students Learn

### Core Concepts Covered

**Primary Keys (PK)**
- Every row in a table needs a unique identifier
- A PK can never be NULL or duplicated
- Examples: StudentID, OrderID, ProductID

**Foreign Keys (FK)**
- How tables link and communicate with each other
- A FK in one table references the PK in another
- Enables relational data without repetition

**First Normal Form (1NF)**
- Each cell must contain exactly one atomic value
- No comma-separated lists inside a column
- No repeating column groups (Subject1, Subject2…)

**Second Normal Form (2NF)**
- Must already be in 1NF
- Every non-key column must depend on the **whole** primary key
- Eliminates partial dependencies

**Third Normal Form (3NF)**
- Must already be in 2NF
- No non-key column should depend on another non-key column
- Eliminates transitive dependencies

> 💡 **Memory trick:** *"Every column depends on the key, the whole key, and nothing but the key!"*

---

## 🧱 Tech Stack

| Layer | Technology |
|-------|-----------|
| Structure | HTML5 |
| Styling | CSS3 (custom properties, grid, flexbox, animations) |
| Logic | Vanilla JavaScript (ES5-compatible) |
| Fonts | Google Fonts — Fraunces (display) + Nunito (body) |
| Dependencies | **None** |
| Build tools | **None** |
| Framework | **None** |

Everything runs in a single `.html` file. Open it in any modern browser and it works.

---


## 📁 File Structure

```
db-quest/
│
├── index.html   # The entire app (self-contained)
├── README.md                    # This file
└── LICENSE                      # MIT License
```

---

## 🎯 Who This Is For

- 👦👧 **Students (ages 10+)** learning databases for the first time
- 👩‍🏫 **Teachers & tutors** who want an engaging classroom or homework resource
- 👨‍💻 **Junior developers** brushing up on database fundamentals
- 📊 **Data analysts** revisiting normalisation concepts
- 🏫 **Anyone** who believes data literacy should be accessible at any age

---

## 🌍 Learn With iKay

**Learn With iKay** is dedicated to making data analysis and tech skills accessible to everyone — regardless of age, background, or experience level. We believe the fundamentals of data are not just for developers or data scientists. They belong to everyone.

> *"No age. No barrier. Just Data."*

Follow our journey and explore more resources:
- LinkedIn: [Learn With iKay](https://www.linkedin.com/company/learn-with-ikay)
- Facebook: [Learn With iKay](https://web.facebook.com/learnwithikay)

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome!

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/add-sql-joins-quiz`
3. Commit your changes: `git commit -m 'Add SQL Joins quiz module'`
4. Push to the branch: `git push origin feature/add-sql-joins-quiz`
5. Open a Pull Request

**Ideas for future contributions:**
- [ ] Add SQL query quiz module
- [ ] Add Entity-Relationship (ER) Diagrams lesson
- [ ] Add a leaderboard using localStorage
- [ ] Add audio feedback for correct/wrong answers
- [ ] Translate to other languages
- [ ] Add more normalization challenge scenarios

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

You are free to use, copy, modify, and distribute this project. Attribution to **Learn With iKay** is appreciated but not required.

---

## 🙏 Acknowledgements

- **[Claude.ai by Anthropic](https://claude.ai)** — for building this entire application through conversation, demonstrating that the barrier between idea and product has never been lower.
- **[Google Fonts](https://fonts.google.com)** — Fraunces and Nunito typefaces.
- Every student who sat through a database lesson and thought *"there has to be a better way to learn this."* This is for you.

---

<div align="center">

**Made with ❤️ by Learn With iKay · Powered by Claude.ai**

*Breaking down data skills for every mind.*

</div>
