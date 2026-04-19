<div align="center">

<br/>

```
 ██████╗ ███████╗ █████╗ ██╗     ██╗████████╗██╗   ██╗
 ██╔══██╗██╔════╝██╔══██╗██║     ██║╚══██╔══╝╚██╗ ██╔╝
 ██████╔╝█████╗  ███████║██║     ██║   ██║    ╚████╔╝ 
 ██╔══██╗██╔══╝  ██╔══██║██║     ██║   ██║     ╚██╔╝  
 ██║  ██║███████╗██║  ██║███████╗██║   ██║      ██║   
 ╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝╚══════╝╚═╝   ╚═╝      ╚═╝  
███████╗██╗███╗   ███╗██╗   ██╗██╗      █████╗ ████████╗ ██████╗ ██████╗ 
██╔════╝██║████╗ ████║██║   ██║██║     ██╔══██╗╚══██╔══╝██╔═══██╗██╔══██╗
███████╗██║██╔████╔██║██║   ██║██║     ███████║   ██║   ██║   ██║██████╔╝
╚════██║██║██║╚██╔╝██║██║   ██║██║     ██╔══██║   ██║   ██║   ██║██╔══██╗
███████║██║██║ ╚═╝ ██║╚██████╔╝███████╗██║  ██║   ██║   ╚██████╔╝██║  ██║
╚══════╝╚═╝╚═╝     ╚═╝ ╚═════╝ ╚══════╝╚═╝  ╚═╝   ╚═╝    ╚═════╝ ╚═╝  ╚═╝
```

<br/>

**Explore alternate histories. Debate the past. Build your multiverse.**

<br/>

[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-Visit_App-e8c547?style=for-the-badge&labelColor=0f1018)](https://your-deployment-url.vercel.app)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-4fc3f7?style=for-the-badge&logo=github&labelColor=0f1018)](https://github.com/yourusername/ai-alternate-simulator)
[![License](https://img.shields.io/badge/License-MIT-a78bfa?style=for-the-badge&labelColor=0f1018)](LICENSE)
[![Made with](https://img.shields.io/badge/Powered_by-Gemini_AI-f06292?style=for-the-badge&labelColor=0f1018)](https://ai.google.dev)

<br/>

![App Screenshot](screenshots/hero.png)
<!-- Replace with your actual screenshot -->

</div>

---

## ⚗️ What is Reality Simulator?

**AI Alternate Reality Simulator** is a domain-specific generative AI chatbot that lets you explore *what could have been*. Ask any "what if" about history, science, or society — and watch the AI map out alternate realities in rich, structured detail.

Built as a **single HTML file** with zero dependencies. No frameworks, no build step, no backend — just pure HTML, CSS, and JavaScript talking directly to the **Google Gemini API**.

> *"What if the Roman Empire never fell?"*  
> *"What if humans never discovered fire?"*  
> *"What if Einstein debated Cleopatra about space exploration?"*

---

## ✨ Five Interaction Modes

| Mode | Icon | Description |
|------|------|-------------|
| **Classic** | ⚡ | Three parallel alternate outcomes with consequences & AI-rated plausibility scores |
| **Timeline** | ⏳ | Traces how a change ripples across Past → Present → Future with key events |
| **Creative** | ✨ | Interactive fiction — co-author branching stories with AI, choose your path |
| **Debate** | ⚖️ | Two historical personas (Einstein, Cleopatra, Sun Tzu...) argue opposing sides |
| **Map** | 🗺️ | Visual node graph of all your explored scenarios — your personal multiverse |

---

## 🚀 Quick Start

### Option 1 — Just open it

```bash
# Clone the repo
git clone https://github.com/yourusername/ai-alternate-simulator.git

# Open in browser — that's literally it
open reality-simulator-v9.html
```

### Option 2 — Deploy to Vercel (recommended)

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel --prod
```

> The app will ask for your **Gemini API key** on first use. It's stored only in your browser session — never sent anywhere except Google's servers.

### Option 3 — GitHub Pages

1. Fork this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, root `/`
4. Your app is live at `https://yourusername.github.io/ai-alternate-simulator`

---

## 🔑 Getting Your API Key

1. Visit [Google AI Studio](https://aistudio.google.com)
2. Click **Get API Key → Create API key**
3. Copy the key (starts with `AIzaSy...`)
4. Paste it into the **API Key panel** inside the app (top-right button)

> The key is stored in `sessionStorage` — it clears when you close the tab. Free tier is sufficient for personal use.

---

## 🎯 Features at a Glance

<details>
<summary><b>⚡ AI Features</b></summary>

- **5 distinct AI modes** — each with a unique prompt schema and JSON contract
- **Probability Scores** — every Classic outcome gets an AI-rated plausibility score (0–100)
- **Consequence Chain** — 5-step cascading butterfly effect from any outcome (Economic → Cultural → Scientific → Political → Biological)
- **Historian Personas** — 11 historical figures (Einstein, Cleopatra, Ada Lovelace, Sun Tzu, Marie Curie...) for Debate mode
- **Scenario Memory** — AI remembers your last 5 queries and weaves connections between alternate realities
- **Plausibility Slider** — controls AI creativity from "wildly speculative" to "historically grounded"

</details>

<details>
<summary><b>🎮 Gamification</b></summary>

- **XP System** — earn points for every interaction
- **15 Achievements** — First Reality, Time Traveller, Butterfly Effect, Orator, Reality Architect...
- **Level System** — level up as your XP grows
- **Reality League** — weekly XP leaderboard (localStorage-based)
- **Daily Challenge** — new what-if prompt every 24 hours with bonus XP

</details>

<details>
<summary><b>🌐 Social Features</b></summary>

- **Community Gallery** — share scenarios publicly, upvote others, remix their ideas
- **Remix & Fork** — one-click remix of any gallery item with your own twist
- **Export & Share** — copy text, generate shareable URL, or publish to gallery

</details>

<details>
<summary><b>🛠️ UI / UX</b></summary>

- **Voice Input** — speak your what-if using Web Speech API, auto-sends when done
- **Reality Compare** — side-by-side split view of two Classic outcomes
- **Smart History** — search, filter by mode, pin, star, and auto-tagged items
- **Custom Templates** — save reusable prompt patterns
- **Multiverse Map** — pannable canvas showing all explored scenarios as connected nodes
- **Dark / Light theme** — full CSS variable-based theming
- **Animated UI** — typewriter cursor, probability bar animations, achievement slide-ins

</details>

---

## 🏗️ Architecture

```
reality-simulator-v9.html          ← Entire app (single file, ~110KB)
│
├── HTML Structure
│   ├── Auth Screen (Login / Register / Guest)
│   ├── Header + Mode Bar
│   ├── Sidebar (Prompts / History / Gallery / League / Badges)
│   └── Chat Area + Input Bar
│
├── CSS (~400 lines)
│   ├── CSS Variables (dark + light themes)
│   ├── Animations (fadeUp, pulse, voicePulse, mapNodePop...)
│   └── Component styles per mode
│
└── JavaScript (~800 lines)
    ├── State Management
    ├── Auth (localStorage)
    ├── API Layer (callGemini)
    ├── Prompt Builder (buildPrompt — 5 schemas)
    ├── Renderers (renderClassic / renderTimeline / renderDebate / renderCreative)
    ├── Multiverse Map (canvas + SVG)
    ├── Voice Input (Web Speech API)
    ├── Social (Gallery, League, Daily Challenge)
    └── Gamification (XP, Achievements, Leaderboard)
```

---

## 🔌 API Integration

The app calls the **Gemini REST API** directly from the browser:

```javascript
// All API calls follow this pattern
const response = await fetch(
  `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.5-flash-lite:generateContent?key=${apiKey}`,
  {
    method: 'POST',
    headers: { 'Content-Type': 'application/json' },
    body: JSON.stringify({
      contents: [{ parts: [{ text: prompt }] }],
      generationConfig: {
        temperature: 0.92,    // High for creative alternate reality generation
        maxOutputTokens: 2000 // Enough for complete multi-field JSON responses
      }
    })
  }
);
```

### Prompt Engineering

Each mode sends a different **JSON schema prompt**:

```
Classic Mode:
  Role: "You are an Alternate Reality AI"
  Schema: { premise, outcomes[{ label, description, consequences[], plausibilityScore }] }

Timeline Mode:
  Role: "You are a Timeline Historian AI"
  Schema: { premise, past, present, future } (each with headline, description, keyEvents[])

Debate Mode:
  Role: "You are a Debate AI. Argue as [Persona] would..."
  Schema: { topic, pro{ argument, points[] }, con{ argument, points[] }, verdict }

Creative Mode:
  Role: "You are a Cinematic Interactive Fiction AI"
  Schema: { emoji, chapter, narrative, choices[] }
```

---

## 📁 Project Structure

```
ai-alternate-simulator/
│
├── reality-simulator-v9.html    ← Main application file
├── README.md                    ← This file
├── LICENSE                      ← MIT License
│
└── screenshots/                 ← Add your screenshots here
    ├── hero.png
    ├── classic-mode.png
    ├── timeline-mode.png
    ├── debate-mode.png
    ├── creative-mode.png
    └── map-mode.png
```

---

## 🖼️ Screenshots

| Classic Mode | Timeline Mode |
|---|---|
| ![Classic](screenshots/classic-mode.png) | ![Timeline](screenshots/timeline-mode.png) |

| Debate Mode | Multiverse Map |
|---|---|
| ![Debate](screenshots/debate-mode.png) | ![Map](screenshots/map-mode.png) |

<!-- Replace placeholder paths with your actual screenshots -->

---

## 🛠️ Tech Stack

| Layer | Technology | Why |
|-------|-----------|-----|
| Frontend | HTML5 + CSS3 + Vanilla JS | Zero dependencies, instant load, no build step |
| AI Model | Google Gemini 2.5 Flash-Lite | Fast, free tier, strong JSON instruction following |
| Voice | Web Speech API (browser native) | No library needed |
| Storage | localStorage + sessionStorage | User data stays on device |
| Fonts | Google Fonts (Syne + DM Sans) | Distinctive typographic personality |
| Hosting | Vercel / Netlify / GitHub Pages | Any static host works |

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl + 1` | Switch to Classic mode |
| `Ctrl + 2` | Switch to Timeline mode |
| `Ctrl + 3` | Switch to Creative mode |
| `Ctrl + 4` | Open Debate / Persona selector |
| `Ctrl + 5` | Open Multiverse Map |
| `Ctrl + Enter` | Send message |
| `Ctrl + N` | New chat |
| `Ctrl + V` | Toggle voice input |
| `Esc` | Clear input |

---

## 🤝 Contributing

Contributions are welcome! Here's how:

```bash
# 1. Fork the repository
# 2. Create a feature branch
git checkout -b feature/your-feature-name

# 3. Make your changes to reality-simulator-v9.html

# 4. Test in browser (just open the file)

# 5. Commit and push
git commit -m "feat: add your feature description"
git push origin feature/your-feature-name

# 6. Open a Pull Request
```

### Ideas for contributions
- New AI modes (e.g., "Scientific" mode — what if a discovery came earlier?)
- More historical personas for Debate mode
- Export to PDF / image
- More achievements
- Multilingual support

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgements

- [Google Gemini API](https://ai.google.dev) — the AI backbone
- [Google Fonts](https://fonts.google.com) — Syne & DM Sans typography
- [Web Speech API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API) — voice input

---

<div align="center">

<br/>

Made with ⚗️ by **Abhinav**

*BTech CSE — INT428 Project Assessment*

<br/>

[![Star this repo](https://img.shields.io/github/stars/yourusername/ai-alternate-simulator?style=social)](https://github.com/yourusername/ai-alternate-simulator)

<br/>

*What reality will you explore next?*

</div>
