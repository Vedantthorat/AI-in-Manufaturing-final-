# 🌐 AI in Manufacturing – Smart Industry Guide

An interactive, AI-supported web platform that helps aspiring entrepreneurs and industry professionals choose the right manufacturing domain — Automotive, Pharmaceuticals, Electronics, Food & Beverages, and more.

The platform delivers data-driven insights on cost estimation, state-wise preferences, industry challenges, and growth opportunities, combined with AI-powered recommendations, Firebase authentication, and a responsive modern UI.

---

## 🧩 Overview

AI in Manufacturing helps users make informed decisions about manufacturing investments by analyzing industry data alongside AI-generated suggestions. It bridges the gap between technology and manufacturing intelligence, acting as a smart guide for new-age entrepreneurs.

---

## 💡 Key Features

| Feature | Description |
|---|---|
| 📍 State-wise Location Insights | Prioritized manufacturing zones within India |
| 📊 Cost Estimations & Future Trends | Predicts approximate setup costs and growth potential |
| ⚙️ Challenges & Opportunities | Highlights industry-specific challenges and possible solutions |
| 🧠 AI-driven Suggestions | Integrates OpenAI API *(in progress)* for intelligent recommendations |
| 🔐 Login & Registration System | Firebase Authentication for user access control |
| 🧮 Investment Calculator | Estimates setup costs, resources, and operational budgets |
| 💬 Chatbot Integration | Planned Q&A assistant powered by OpenAI |
| 💻 Responsive Design | Modern UI/UX inspired by real industrial dashboards, with animations and sidebar navigation |
| 🚀 Performance Optimized | Lightweight, fast, and accessible across all devices |

---

## 🛠️ Tech Stack

| Category | Technologies |
|---|---|
| Frontend | HTML5, CSS3, JavaScript (ES6+) |
| Backend / Auth | Firebase Authentication |
| AI Integration | OpenAI API *(planned)* |
| Design | Responsive layout, animated components |
| Deployment | GitHub Pages / Firebase Hosting |

---

link : https://solutionofindustrybyai.netlify.app/index.html#

## 🧠 Architecture Highlights

- Modular structure for easy scalability
- Separate JS modules for calculator, login/auth, and chatbot integration
- CSS animations for smooth transitions
- Firebase connection for login and registration
- Planned backend for AI model integration (OpenAI API)

---

## 📁 Project Structure

```
ai-in-manufacturing/
├── index.html              # Home page
├── login.html               # Login / Registration page
├── calculator.html          # Investment calculator
├── enquiry.html              # Industry enquiry form
├── css/
│   └── styles.css
├── js/
│   ├── calculator.js
│   ├── auth.js
│   └── chatbot.js            # Planned
├── assets/
│   └── images/
└── README.md
```

> Update this tree to match your actual folder layout if it differs.

---

## 🖼️ UI Preview

### 🏠 Home Page
<img width="1892" height="818" alt="image" src="https://github.com/user-attachments/assets/c121dce2-8f33-4730-a1b0-3887314797dc" />


### 🔐 Login Page
<img width="585" height="556" alt="image" src="https://github.com/user-attachments/assets/ada6a7a8-ba80-4619-aa96-4bdd1fe68367" />


### 🧮 Industry Calculator
<img width="865" height="862" alt="image" src="https://github.com/user-attachments/assets/8834e38b-5616-4577-afdf-18470f04ceca" />


### 📝 Industry Enquiry Form
<img width="613" height="717" alt="image" src="https://github.com/user-attachments/assets/fab3f87f-9665-4ffd-b343-3d1afb50f42f" />


> Replace the paths above with your actual screenshot files (e.g. place them in `assets/images/` and rename to match, or update the paths to point wherever your images live).

---

## ⚙️ Getting Started

### Prerequisites
- A modern web browser
- [Firebase](https://firebase.google.com/) project (for authentication)
- (Optional, for AI features) An OpenAI API key

### Installation

```bash
# Clone the repository
git clone https://github.com/Vedantthorat/ai-in-manufacturing.git

# Navigate into the project
cd ai-in-manufacturing

# Open index.html directly, or serve locally
npx serve .
```

### Firebase Setup
1. Create a project in the [Firebase Console](https://console.firebase.google.com/).
2. Enable **Authentication** (Email/Password or preferred provider).
3. Copy your Firebase config into `js/auth.js`.

### OpenAI Setup *(planned)*
1. Obtain an API key from [OpenAI](https://platform.openai.com/).
2. Add it to your environment configuration (never commit keys to source control).

---

## 🗺️ Roadmap

- [ ] Integrate OpenAI API for AI-driven recommendations
- [ ] Launch chatbot for Q&A assistance
- [ ] Expand state-wise dataset coverage
- [ ] Add user dashboard with saved calculations
- [ ] Deploy production build to Firebase Hosting

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to open a pull request or raise an issue.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License — see the `LICENSE` file for details.

---

## 📬 Contact

**Vedant Thorat**
- GitHub: [github.com/Vedantthorat](https://github.com/Vedantthorat)
- Portfolio: [vedantthoratportfolio1.netlify.app](https://vedantthoratportfolio1.netlify.app)
