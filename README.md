# 🛡️ Parry Security – Cyber Safety Awareness Training Platform
 
![Version](https://img.shields.io/badge/version-1.0.0-teal)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/license-MIT-green)
 
> **An interactive, self-paced cyber security training platform with 6 comprehensive modules, gamified assessments, and professional certification.**
 
[Live Demo](#) • [Report Bug](#) • [Request Feature](#)
 
---
 
## 📋 Table of Contents
 
- [About The Project](#-about-the-project)
- [Key Features](#-key-features)
- [Demo Screenshots](#-demo-screenshots)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [How It Works](#-how-it-works)
- [User Journey](#-user-journey)
- [Technical Stack](#-technical-stack)
- [File Descriptions](#-file-descriptions)
- [Browser Support](#-browser-support)
- [Future Enhancements](#-future-enhancements)
- [Contributing](#-contributing)
- [License](#-license)
- [Acknowledgments](#-acknowledgments)
- [Contact](#-contact)
 
---
 
## 📖 About The Project
 
**Parry Security Cyber Safety Awareness Training Platform** is a complete, front-end based e-learning solution designed to educate individuals and organisations about cyber threats and safe online behaviour.
 
### Why This Project?
 
With **82% of data breaches involving human error**, traditional security training is often boring and forgettable. This platform bridges the knowledge gap by turning cyber security awareness into an **engaging, interactive, gamified experience**.
 
### What Problem Does It Solve?
 
| Problem | Solution |
|---------|----------|
| ❌ Boring PDF training | ✅ Interactive exercises & quizzes |
| ❌ No progress tracking | ✅ Real-time progress bar & localStorage |
| ❌ No proof of completion | ✅ Professional certificate with PDF download |
| ❌ One-size-fits-all | ✅ Self-paced learning with 6 modules |
| ❌ No engagement | ✅ Achievement badges & confetti animations |
 
---
 
## ⭐ Key Features
 
### 🔐 Authentication System
- **Signup** with email verification & password strength meter
- **Login** with demo account support
- **Forgot Password** with 6-digit reset code
- **Reset Password** with confirmation
 
### 📚 6 Interactive Lessons
 
| # | Lesson | Key Topics |
|---|--------|------------|
| 1 | Phishing & Suspicious Links | Email analysis, URL safety checker, typosquatting |
| 2 | Social Engineering & Impersonation | Vishing, smishing, pretexting, real scenarios |
| 3 | Risky Online Behaviour | Password reuse, oversharing, update delays |
| 4 | Password Security & 2FA | Strength meter, credential stuffing, 2FA benefits |
| 5 | Public Wi-Fi & Mobile Security | VPNs, MITM attacks, mobile app permissions |
| 6 | Data Privacy & Social Media | Digital footprint, data brokers, privacy settings |
 
### 🎮 Interactive Elements
- **Spot the Phishing Email** – Compare real vs fake emails
- **URL Safety Analyzer** – Test links before clicking
- **Password Strength Meter** – Real-time password testing
- **Choice-Based Scenarios** – Learn consequences of decisions
- **Interactive Checklists** – Identify risky behaviours
- **Achievement Badges** – 5 badges per lesson
 
### 📝 Knowledge Checks
- **6 end-of-lesson quizzes** (4 questions each)
- **Final comprehensive quiz** (20 questions)
- **Topic-wise performance breakdown**
- **Perfect score requirement (20/20) for certificate**
 
### 🏆 Certificate System
- Auto-populates user's name from signup
- Professional A4 landscape design
- Digital signature (Mudassar Ali Raja, CSO)
- Unique certificate ID
- One-click PDF download
- Print functionality
 
### 📊 Progress Tracking
- Real-time progress bar (0% → 100%)
- Step-by-step lesson indicators
- Persistent storage via localStorage
- Resume anytime from where you left off
 
### 🎨 User Experience
- Fully responsive design (mobile, tablet, desktop)
- Smooth animations & transitions
- Professional light color scheme (teal/purple gradient)
- Custom modal popups (no browser alerts)
- Confetti animation on perfect score
 
---
 
## 📸 Demo Screenshots
 
```
┌─────────────────────────────────────────────────────────────────┐
│  🛡️ PARRY SECURITY                                    [Login] [Signup] │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│              🎓 Final Knowledge Quiz                           │
│         Test your understanding of all 6 modules               │
│                                                                 │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │  📝 Question 5/20                    Parry Security     │   │
│  │                                                          │   │
│  │  What is 'vishing'?                                     │   │
│  │                                                          │   │
│  │  ○ Phishing via email                                    │   │
│  │  ○ Phishing via SMS text                                │   │
│  │  ● Phishing via phone call ✓                            │   │
│  │  ○ Phishing via social media DMs                        │   │
│  │                                                          │   │
│  │  ✅ Correct! Vishing = Voice phishing                   │   │
│  │                                                          │   │
│  │  [← Previous]              [Next →]                     │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                                 │
│  ○ ○ ● ○ ○ ○ ○ ○ ○ ○ ○ ○ ○ ○ ○ ○ ○ ○ ○ ○                      │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```
 
```
┌─────────────────────────────────────────────────────────────────┐
│                    PARRY SECURITY                               │
│           CERTIFICATE OF COMPLETION                             │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│         This certificate is proudly presented to               │
│                 ┌─────────────────────┐                        │
│                 │     John Doe         │                        │
│                 └─────────────────────┘                        │
│                                                                 │
│   ✅ Has completed all 6 training modules with distinction     │
│                                                                 │
│   ┌─────────────────────────────────────────────────────┐      │
│   │  ✓ Phishing    ✓ Social Eng.   ✓ Risky Behaviour   │      │
│   │  ✓ Password    ✓ Public Wi-Fi  ✓ Data Privacy      │      │
│   └─────────────────────────────────────────────────────┘      │
│                                                                 │
│   ──────────────    ──────────────    ──────────────           │
│   Mudassar A. Raja     John Doe        March 15, 2025          │
│   (Chief Security Officer)  (Participant)   (Date of Issue)    │
│                                                                 │
├─────────────────────────────────────────────────────────────────┤
│  ID: PS-2025-4821  │  🔒 Verify online  │  © Parry Security    │
└─────────────────────────────────────────────────────────────────┘
```
 
---
 
## 📁 Project Structure
 
```
parry-security-training/
│
├── 📄 index.html                 # Signup page with email verification
├── 📄 login.html                 # Login page with forgot password
├── 📄 forgot-password.html       # Request reset code
├── 📄 reset-password.html        # Create new password
│
├── 📄 lesson1.html               # Phishing & Suspicious Links
├── 📄 lesson2.html               # Social Engineering & Impersonation
├── 📄 lesson3.html               # Risky Online Behaviour
├── 📄 lesson4.html               # Password Security & 2FA
├── 📄 lesson5.html               # Public Wi-Fi & Mobile Security
├── 📄 lesson6.html               # Data Privacy & Social Media
│
├── 📄 quiz.html                  # Final 20-question assessment
├── 📄 certificate.html           # Certificate of completion
│
└── 📁 assets/ (optional)         # Images, icons, fonts
```
 
---
 
## 🚀 Getting Started
 
### Prerequisites
 
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- No server required – runs entirely in the browser
- No internet connection needed (after initial load)
 
### Installation
 
1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/parry-security-training.git
   ```
 
2. **Navigate to the project folder**
   ```bash
   cd parry-security-training
   ```
 
3. **Open the application**
   - Double-click `index.html` OR
   - Use a local server:
     ```bash
     # Using Python
     python -m http.server 8000
     # Using VS Code Live Server
     Right-click index.html → Open with Live Server
     ```
 
4. **Start training**
   - Sign up with your name and email
   - OR use demo account: `demo@parrysecurity.com` / `demo123`
   - Complete all 6 lessons
   - Take the final quiz (score 20/20)
   - Download your certificate!
 
---
 
## 🔄 How It Works
 
### Data Flow Diagram
 
```
┌──────────┐    ┌──────────┐    ┌──────────┐    ┌──────────┐
│  Signup  │───▶│  Login   │───▶│ Lesson 1 │───▶│ Lesson 2 │
└──────────┘    └──────────┘    └──────────┘    └──────────┘
                                                      │
                                                      ▼
┌──────────┐    ┌──────────┐    ┌──────────┐    ┌──────────┐
│ Lesson 6 │◀───│ Lesson 5 │◀───│ Lesson 4 │◀───│ Lesson 3 │
└──────────┘    └──────────┘    └──────────┘    └──────────┘
      │
      ▼
┌──────────┐    ┌──────────┐    ┌──────────┐
│   Quiz   │───▶│ Perfect? │───▶│Certificate│
└──────────┘    └──────────┘    └──────────┘
                     │
                     ▼ (No)
              ┌──────────┐
              │ Retake   │
              │ Quiz     │
              └──────────┘
```
 
### localStorage Schema
 
| Key | Description | Example |
|-----|-------------|---------|
| `parryUsers` | All registered users | `[{fullName, email, password, ...}]` |
| `parryCurrentUser` | Currently logged in user | `{email, fullName, loginTime}` |
| `parryTraineeName` | User's name for certificate | `"John Doe"` |
| `parryLesson1Completed` | Lesson 1 completion status | `"true"` |
| `parryQuizScore` | Final quiz score | `20` |
| `parryBadges` | Earned achievement badges | `["badge1","badge2"]` |
 
---
 
## 👤 User Journey
 
```
┌─────────────────────────────────────────────────────────────────────────┐
│                          COMPLETE USER JOURNEY                          │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                         │
│  📝 Signup ──▶ 🔐 Login ──▶ 📧 Lesson 1 ──▶ 🎭 Lesson 2                 │
│      │              │            │              │                      │
│      ▼              ▼            ▼              ▼                      │
│  Email Verify   Dashboard    Phishing      Social Eng.                  │
│                                    │                                    │
│                                    ▼                                    │
│  🔒 Lesson 6 ◀── 📶 Lesson 5 ◀── 🔑 Lesson 4 ◀── ⚠️ Lesson 3            │
│       │              │              │              │                   │
│       ▼              ▼              ▼              ▼                   │
│   Data Privacy   Public Wi-Fi   Password      Risky Behaviour          │
│       │                                                               │
│       ▼                                                               │
│  📝 Final Quiz (20 questions)                                         │
│       │                                                               │
│       ▼                                                               │
│  🏆 Score 20/20?                                                      │
│       │                                                               │
│   ┌───┴───┐                                                           │
│   ▼       ▼                                                           │
│  YES     NO                                                           │
│   │       │                                                           │
│   ▼       ▼                                                           │
│ 📜      🔄 Retake Quiz                                                │
│Certificate                                                            │
│   │                                                                   │
│   ▼                                                                   │
│ 🖨️ Download PDF / Print                                              │
│                                                                       │
└─────────────────────────────────────────────────────────────────────────┘
```
 
---
 
## 💻 Technical Stack
 
| Technology | Purpose |
|------------|---------|
| **HTML5** | Structure & semantics |
| **CSS3** | Styling, animations, responsive design |
| **CSS Variables** | Theming & consistent colors |
| **Flexbox & Grid** | Modern layouts |
| **Vanilla JavaScript** | All interactivity (no frameworks) |
| **LocalStorage API** | Persistent user data & progress |
| **html2pdf.js** | PDF certificate generation |
| **Google Fonts** | Sora & Figtree typography |
 
### No Dependencies Required
 
This project uses **zero external dependencies** (except html2pdf for PDF generation). Everything is pure HTML/CSS/JS.
 
---
 
## 📄 File Descriptions
 
| File | Description |
|------|-------------|
| `index.html` | Signup page with email verification modal |
| `login.html` | Login page with forgot password link |
| `forgot-password.html` | Request 6-digit reset code |
| `reset-password.html` | Create new password with strength meter |
| `lesson1.html` | Phishing: email analysis, URL checker, 4-quiz |
| `lesson2.html` | Social Eng: scenarios, vishing/smishing, 4-quiz |
| `lesson3.html` | Risky behaviour: checklist, statistics, 4-quiz |
| `lesson4.html` | Password: strength tester, 2FA, 4-quiz |
| `lesson5.html` | Public Wi-Fi: VPN info, scenario, 4-quiz |
| `lesson6.html` | Data privacy: checklist glossary, 4-quiz |
| `quiz.html` | 20-question final assessment with topic breakdown |
| `certificate.html` | Professional certificate with PDF/print |
 
---
 
## 🌐 Browser Support
 
| Browser | Version | Status |
|---------|---------|--------|
| Chrome | 90+ | ✅ Fully supported |
| Firefox | 88+ | ✅ Fully supported |
| Safari | 14+ | ✅ Fully supported |
| Edge | 90+ | ✅ Fully supported |
| Opera | 76+ | ✅ Fully supported |
| Mobile Chrome | Latest | ✅ Responsive |
| Mobile Safari | Latest | ✅ Responsive |
 
---
 
## 🚀 Future Enhancements
 
- [ ] **Admin Dashboard** – Track all users and their progress
- [ ] **Dark Mode** – User preference toggle
- [ ] **EmailJS Integration** – Send real verification emails
- [ ] **Session Timeout** – Auto-logout after inactivity
- [ ] **Progress Export** – Download progress as CSV
- [ ] **Leaderboard** – Compare progress with others
- [ ] **Video Tutorials** – Embedded explainer videos
- [ ] **Multi-language** – Spanish, French, German support
- [ ] **PWA Support** – Install as mobile app
- [ ] **Backend Integration** – Node.js/Express + MongoDB
 
---
 
## 🤝 Contributing
 
Contributions are welcome! Please follow these steps:
 
1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add amazing feature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/amazing-feature
   ```
5. **Open a Pull Request**
 
### Guidelines
 
- Keep code clean and well-commented
- Maintain responsive design
- Test across multiple browsers
- Update documentation as needed
 
---
 
## 📜 License
 
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.
 
```
MIT License
 
Copyright (c) 2025 Parry Security
 
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files...
```
 
---
 
## 🙏 Acknowledgments
 
- **Fonts**: [Google Fonts](https://fonts.google.com) – Sora & Figtree
- **PDF Generation**: [html2pdf.js](https://github.com/eKoopmans/html2pdf.js)
- **Icons**: Emoji icons for visual enhancement
- **Inspiration**: Real-world cyber security training standards
 
---
 
## 📧 Contact
 
**Mudassar Ali Raja** – [GitHub](https://github.com/yourusername)
 
**Project Link:** [https://github.com/yourusername/parry-security-training](https://github.com/yourusername/parry-security-training)
 
**Demo Link:** [https://yourdomain.com/parry-security](https://yourdomain.com/parry-security)
 
---
 
## ⭐ Show Your Support
 
If you found this project helpful, please give it a ⭐ on GitHub!
 
---
 
```
┌─────────────────────────────────────────────────────────────────┐
│  🛡️ PARRY SECURITY                                              │
│  Your Digital Shield – Empowering Safe Online Choices           │
│                                                                 │
│  "Security is not a product, it's a process."                  │
│                                              – Bruce Schneier   │
└─────────────────────────────────────────────────────────────────┘
```
 
---
 
## 📊 Project Statistics
 
| Metric | Value |
|--------|-------|
| **Total Pages** | 10 |
| **Total Lessons** | 6 |
| **Quiz Questions** | 20 + (6×4) = 44 |
| **Interactive Exercises** | 15+ |
| **Achievement Badges** | 30+ |
| **Lines of Code** | ~8,000 |
| **Time to Complete** | 60-75 minutes |
| **Storage** | 100% LocalStorage |
 
---
 
**Built with ❤️ for cyber safety awareness**
