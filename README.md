# 🚀 AZ-400 Study Hub

> An interactive, browser-based study guide for the **Microsoft AZ-400: Designing and Implementing Microsoft DevOps Solutions** certification exam.

🌐 **Live Demo:** [leonmc00.github.io/az400-study-hub/az400-study-hub-v2.html](https://leonmc00.github.io/az400-study-hub/az400-study-hub-v2.html)


---

## 📖 About

This project was built as a hands-on alternative to reading through walls of text. It covers all five AZ-400 exam domains with a mix of interactive activities designed to reinforce learning through doing rather than just reading.

Built with plain HTML, CSS, and vanilla JavaScript — no frameworks, no dependencies, no build steps. Open the file in any browser and it works.

---

## ✨ Features

### 📚 Domain Overview
All five exam domains with expandable cards covering theory, key topics, and tools — each with hands-on activities built in.

| Domain | Exam Weight |
|--------|------------|
| D1 — Processes & Communications | 10–15% |
| D2 — Source Control Strategy | 10–15% |
| D3 — Build & Release Pipelines | 50–55% 🔥 |
| D4 — Security & Compliance | 10–15% |
| D5 — Instrumentation Strategy | 5–10% |

### 🃏 Flashcards
Click-to-flip flashcards covering must-know definitions for each domain. Covers DORA metrics, branching strategies, security scanning types, SRE terminology, and more.

### 🧩 Drag & Drop Exercises
Match terms to definitions, strategies to use cases, and tools to scenarios. Immediate visual feedback — correct drops turn green, wrong drops shake and return.

### ⚙️ YAML Pipeline Builder *(Domain 3)*
Build a real Azure Pipelines YAML file block by block. Each block added reveals a tip explaining what it does and why it matters in a real pipeline.

### 🚀 Build-a-Pipeline Challenge *(Domain 3)*
A four-step guided scenario where you make decisions to build a production-ready CI/CD pipeline. Steps unlock sequentially with full explanations for correct and incorrect answers.

### 🎯 Scenario Challenges
Eight exam-style scenario questions covering all domains. Each question includes context, four answer options, and a detailed explanation of why the correct answer is right — and why the others are wrong.

### ⚡ Cheat Sheets
Visual quick-reference cards covering branching strategies, deployment patterns, DORA metrics, secrets management, IaC options, and security scanning types side by side.

### 💡 Exam Tips
Study timeline, exam logistics, what to prioritise, and common exam traps — including the things the AZ-400 exam consistently tests.

---

## 🗂️ Repository Structure

```
az400-study-hub/
├── az400-study-hub-v2.html    # Main application — all content and logic
└── README.md                  # This file
```

Everything is contained in a single HTML file for simplicity. No build process, no dependencies.

---

## 🚀 Getting Started

### Option 1 — Live via GitHub Pages
Once GitHub Pages is enabled (Settings → Pages → Deploy from branch: main), the app is available at:
```
https://your-username.github.io/az400-study-hub/az400-study-hub-v2.html
```

### Option 2 — Run locally
Clone the repository and open the HTML file directly in your browser:
```bash
git clone https://github.com/your-username/az400-study-hub.git
cd az400-study-hub
# Open az400-study-hub-v2.html in your browser
```
No server or build step required.

---

## ✏️ Contributing & Updating

Contributions, corrections, and improvements are welcome. The exam content is updated periodically by Microsoft, so keeping the material current is always valuable.

### Editing directly on GitHub
1. Navigate to `az400-study-hub-v2.html` in the repository
2. Click the **pencil icon** (Edit this file)
3. Make your changes
4. Add a commit message describing what you changed
5. Click **Commit changes**

GitHub Pages will automatically redeploy within approximately 60 seconds.

### Editing locally
```bash
git clone https://github.com/your-username/az400-study-hub.git
# Edit az400-study-hub-v2.html in your editor of choice
git add .
git commit -m "Your change description"
git push origin main
```

### Areas where contributions are particularly welcome
- Additional scenario challenge questions
- New flashcard sets for any domain
- New drag and drop exercises
- Corrections to any exam content
- Accessibility improvements

---

## 📋 Exam Reference

| Detail | Value |
|--------|-------|
| Exam code | AZ-400 |
| Full name | Designing and Implementing Microsoft DevOps Solutions |
| Certification | Microsoft Certified: DevOps Engineer Expert |
| Passing score | 700 / 1000 |
| Exam cost | ~$165 USD |
| Prerequisite | AZ-104 or AZ-204 |
| Renewal | Annual free online assessment |
| Official study guide | [learn.microsoft.com/credentials/certifications/exams/az-400](https://learn.microsoft.com/en-us/credentials/certifications/exams/az-400) |

---

## 📌 Disclaimer

This project is an independent study aid and is not affiliated with, endorsed by, or produced by Microsoft. All exam content is based on the publicly available AZ-400 skills outline. Always refer to the [official Microsoft study guide](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/az-400) for the most current and authoritative information.

---

## 📄 Licence

This project is open source and available under the [MIT Licence](LICENSE).

---

*Built to make AZ-400 exam prep less painful. Good luck! 🎯*
