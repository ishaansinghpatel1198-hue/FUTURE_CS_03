# 🎣 PhishGuard — Phishing Email Detection & Awareness System

> Cyber Security Internship — Future Interns | Task 02 | Track Code: **CS**

PhishGuard is an interactive web application that analyzes emails for phishing indicators in real time, classifies them as **Safe**, **Suspicious**, or **Phishing**, and educates users on common social engineering techniques.

🔗 **Live Demo:** *(add GitHub Pages link here if hosted)*
📄 **Full Report:** [Phishing_Detection_Awareness_Report.pdf](./Phishing_Detection_Awareness_Report_FUTURE_CS_02.pdf)

---

## 🚀 Features

- **Real-time email analysis** — paste sender, subject, body, and headers for instant risk scoring
- **Risk scoring engine** — weighted detection across 15+ phishing indicators
- **Header authentication checks** — flags SPF / DKIM / DMARC failures
- **4 built-in sample emails** — bank phishing, prize scam, IT impersonation, and a legitimate email for comparison
- **Awareness Guide** — explains 6 real-world phishing techniques in plain language
- **Prevention checklist** — tailored guidance based on the verdict
- **Zero dependencies** — single HTML file, runs entirely in the browser

## 🛠️ Tools & Technologies

- HTML5 / CSS3 / Vanilla JavaScript
- Pattern-matching & heuristic analysis (regex-based indicator detection)
- Email header authentication parsing (SPF/DKIM/DMARC)

## 📊 How It Works

1. User submits email details (sender, subject, body, headers)
2. The engine scans for indicators across 4 categories: sender identity, subject language, body content, and header authentication
3. Each indicator adds a weighted risk score (0–100)
4. Final verdict: **Safe** (<25), **Suspicious** (25–54), or **Phishing** (≥55)
5. User receives a breakdown of detected indicators plus tailored prevention tips

## 📁 Files

| File | Description |
|---|---|
| `PhishGuard_WebApp_FUTURE_CS_02.html` | Interactive web application |
| `Phishing_Detection_Awareness_Report_FUTURE_CS_02.pdf` | Full assessment report with sample analysis, indicator classification, and prevention guidelines |

## 🎓 Skills Demonstrated

Phishing detection · Email threat analysis · Security awareness content design · Risk classification · Client-ready documentation

## 👤 Author

*(Your Name)* — Cyber Security Intern, Future Interns
[LinkedIn](#) | [Portfolio](#)

---

*This project was built as part of the Future Interns Cyber Security internship program (futureinterns.com).*
