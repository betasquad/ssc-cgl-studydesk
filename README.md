# 🎓 SSC CGL — StudyDesk

A fully offline, single-file study portal built for SSC CGL preparation.  
No installation. No login. No server. Just open `index.html` in Chrome and study.

🌐 **Live:** [yourusername.github.io/ssc-cgl-studydesk](https://yourusername.github.io/ssc-cgl-studydesk)

---

## ✨ Features

### 📂 Study View
- **Open any local folder** of PDFs and videos directly in the browser (no uploading)
- Subfolders are scanned automatically — one click loads everything
- **Folder memory** — re-grants permission automatically on next visit
- Supports `.pdf`, `.mp4`, `.mkv`, `.webm`, `.avi`, `.mov`, `.mp3`, `.m4a` and more
- **Video timestamp saving** — resumes exactly where you left off
- **Playback speed control** — 0.5× to 2× in one click
- **Mark files as done** — with completion date shown in sidebar
- **File progress bars** per folder group (e.g. 3/12 done)
- **Jump to first unseen** — skips straight to your next unfinished file
- **Filter** by All / PDF / Video / Done
- **Sort** by Name, Z→A, Unseen first, or Type
- **Folder collapse** to keep sidebar clean

### ⏱ Pomodoro Timer
- Built into the study toolbar — always visible while studying
- 25-minute work sessions, 5-minute breaks
- Session counter tracks 🍅 completed today
- Study time is automatically logged when a session completes
- Keyboard shortcut: `P`

### 🏠 Home Dashboard
| Card | What it shows |
|---|---|
| 📅 Date Banner | Today's date, days studied, current streak 🔥 |
| 🎯 Exam Goal | Set your exam name + date, see days/weeks/months countdown |
| ⏱ Study Time | Today's time, all-time total, pomodoros today, days tracked |
| 📋 Today's Topics | Pulled from your uploaded Excel schedule |
| 📊 Resources Completed | PDFs and videos done per subject |
| ✅ Study Status | Check off GA / English / Reasoning / Maths for today |
| 🕐 Recently Opened | Last 8 files across all subjects with timestamps |
| 📅 Activity Heatmap | 16-week GitHub-style heatmap of study days |
| 📈 Overall Progress | Days studied, streak, completion % |
| 🧩 Subject-wise | Completion breakdown per subject |
| 📌 Almost Days | Days where you were close but didn't hit the minimum |

### 🗂 Subjects
| # | Subject | Shortcut |
|---|---|---|
| 1 | ✍️ Grammar | `1` |
| 2 | 📖 Vocabulary | `2` |
| 3 | 🌍 General Studies | `3` |
| 4 | 📰 Current Affairs | `4` |
| 5 | 📝 NCERT Notes | `5` |
| 6 | ➗ Mathematics | `6` |
| 7 | 🧠 Reasoning | `7` |
| 8 | 💻 Computer | `8` |

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|---|---|
| `←` / `→` | Previous / Next file |
| `1` – `8` | Switch subject |
| `Space` | Toggle current file as done |
| `P` | Start / Pause Pomodoro |
| `F` | Toggle fullscreen |
| `S` | Toggle sidebar |
| `H` | Hide / show header (more screen space) |
| `?` | Show shortcut hint |

---

## 📅 Excel Schedule Upload

Upload a `.xlsx` file to see today's topics automatically on the home screen.

**Required columns:**

| Column | Accepted names |
|---|---|
| Date | `date` |
| General Awareness | `general`, `ga`, `aware` |
| English | `english`, `eng` |
| Reasoning | `reason`, `rsn` |
| Mathematics | `math` |

Each cell can have multiple entries separated by newlines.  
Use `Label: value` format for page numbers, e.g. `Polity: Ch 3–5`.

---

## 🚀 How to Use Locally

1. Download `index.html`
2. Open it in **Chrome or Edge** (desktop)
3. Click the **SSC CGL** logo to go to the home dashboard
4. Click any subject in the navbar → **Open Folder** → pick your study folder
5. Files load instantly — progress saves automatically

> ⚠️ **Requires Chrome or Edge desktop.** The folder access feature uses the [File System Access API](https://developer.mozilla.org/en-US/docs/Web/API/File_System_Access_API) which is not supported in Safari or Firefox.

---

## 💾 Data & Privacy

- **Everything is stored locally** in your browser (`localStorage` + `IndexedDB`)
- No data is ever sent to any server
- No account, no tracking, no analytics
- Clearing browser cache will erase your progress — export/backup feature coming soon

---

## 🛠 Tech Stack

| | |
|---|---|
| Language | Vanilla HTML / CSS / JavaScript |
| Dependencies | [SheetJS (XLSX)](https://sheetjs.com/) — CDN only, for schedule upload |
| Storage | `localStorage` + `IndexedDB` |
| Fonts | Google Fonts — Outfit, Lora |
| Hosting | GitHub Pages |

No framework. No build step. No `node_modules`. The entire app is one file.

---

## 📁 Project Structure

```
ssc-cgl-studydesk/
├── index.html      ← The entire app
└── README.md       ← This file
```

---

## 🙌 Contributing

This is a personal study tool — feel free to fork and adapt it for your own exam prep.  
If you find a bug or have a suggestion, open an issue!

---

*Built for focused, distraction-free exam preparation.*
