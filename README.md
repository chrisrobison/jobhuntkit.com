# JobHuntKit 🎯

**Your personal job search command center.**

Track applications, tailor resumes with AI, and stay organized — all in one place. Your data stays on your device.

[![Live Site](https://img.shields.io/badge/Live-jobhuntkit.com-blue?style=for-the-badge)](https://jobhuntkit.com)
[![App](https://img.shields.io/badge/Open-App-green?style=for-the-badge)](https://jobhuntkit.com/app/)

---

## ✨ Features

- **📋 Job Tracking** — Manage applications with status, notes, and deadlines
- **📄 Resume Builder** — JSON Resume-based editor with multiple versions
- **✉️ Cover Letters** — Generate and store tailored cover letters
- **🤖 AI Assistant** — Tailor resumes, analyze job matches, generate content
- **🔍 Job Search** — Integrated job feed aggregation
- **📊 Analytics** — Track your application pipeline and success rates
- **🔒 Privacy-First** — All data stored locally in your browser (IndexedDB)
- **📱 Works Everywhere** — Responsive design for desktop and mobile

## 🚀 Quick Start

Just visit [jobhuntkit.com/app](https://jobhuntkit.com/app/) — no signup required!

Your data is stored locally in your browser. Export anytime to back up or transfer.

## 💎 Pro Features

| Free | Pro ($7.99/mo or $79 lifetime) |
|------|-------------------------------|
| Unlimited job tracking | Everything in Free |
| 1 resume version | Unlimited resume versions |
| Basic job scraper | AI-powered resume tailoring |
| Local storage | AI cover letter generation |
| Export to PDF | Job match analysis |
| | Priority support |

## 🏗️ Project Structure

```
├── index.html          # Landing page
├── jobs.css            # Shared styles
├── activate.html       # License activation
├── checkout-success.html
├── downloads/          # Browser extension
└── app/                # Main application (submodule)
    └── → chrisrobison/resume-tool
```

The `/app` directory is a [git submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules) pointing to the main application repository.

## 🛠️ Development

```bash
# Clone with submodules
git clone --recurse-submodules https://github.com/chrisrobison/jobhuntkit.com.git

# Or if already cloned
git submodule update --init --recursive

# Update app to latest
git submodule update --remote app
```

## 📄 License

MIT © [Christopher Robison](https://github.com/chrisrobison)

---

**Built with vanilla JavaScript, Web Components, and zero framework dependencies.**
