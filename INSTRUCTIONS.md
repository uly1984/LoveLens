\# INSTRUCTIONS.md  

LoveLens — Installation, Setup, and Customization Guide 💗



LoveLens is designed to be simple, portable, and easy to run on any system.  

This guide explains how to install, customize, and use LoveLens locally or as a SellAITool product.



\---



\# 1. 📦 Folder Structure



Your LoveLens project should look like this:



LoveLens/

│

├── README.md

├── SYSTEM\_PROMPT.md

├── INSTRUCTIONS.md

├── CHANGELOG.md

├── LICENSE.md

│

├── demo/

│   ├── index.html

│   ├── style.css

│   └── demo\_screenshot.png

│

├── assets/

│   ├── logo.png

│   ├── banner.png

│   └── icon.png

│

├── prompts/

│   ├── warm\_mode.txt

│   ├── playful\_mode.txt

│   └── deep\_mode.txt

│

└── release/

&#x20;   └── LoveLens\_v1.0.txt



\---



\# 2. 🚀 Running LoveLens Locally (Offline)



LoveLens works with any local LLM that supports custom system prompts.



\### Compatible with:

\- LM Studio  

\- Ollama  

\- GPT4All  

\- KoboldCpp  

\- Text-generation-webui  

\- Jan.ai  

\- Anything that accepts a system prompt  



\### Steps:



1\. Open your preferred local LLM app  

2\. Create a new model/chat profile  

3\. Copy the entire contents of `SYSTEM\_PROMPT.md`  

4\. Paste it into the \*\*System Prompt\*\* or \*\*Instruction\*\* field  

5\. Start chatting with LoveLens 💗



That’s it — no installation required.



\---



\# 3. 🎭 Switching Personality Modes



LoveLens includes three optional personality modes stored in `/prompts/`:



\- `warm\_mode.txt`  

\- `playful\_mode.txt`  

\- `deep\_mode.txt`  



\### To switch modes:

Copy the contents of the mode file and paste it \*\*after\*\* the main system prompt.



Example:



Modes can be swapped at any time.

---

# 4. 🎨 Customizing LoveLens

You can customize:

### ✔ Tone  
Modify the “Core Personality” section in `SYSTEM_PROMPT.md`.

### ✔ Emojis  
Adjust the emoji palette to match your brand.

### ✔ Boundaries  
Edit the “Safety & Stability” section.

### ✔ Branding  
Replace images in `/assets/` with your own logo, banner, and icon.

### ✔ Demo Page  
Edit `/demo/index.html` and `/demo/style.css`.

---

# 5. 🌐 Hosting the Demo Page

You can host the demo page on:

### GitHub Pages  
1. Push the repo to GitHub  
2. Go to **Settings → Pages**  
3. Select the `main` branch  
4. Set folder to `/root`  
5. Save  

### Netlify / Vercel  
Drag the folder into their dashboard.

### Localhost  
Just open `demo/index.html` in your browser.

---

# 6. 📦 Creating a Release Version

The `/release/` folder contains:



This file should include:

- The full system prompt  
- Any add‑on modes  
- Version number  
- Notes for buyers  

This is the file you upload to SellAITool.

---

# 7. 🛠 Updating LoveLens

Whenever you update the project:

1. Edit the relevant file  
2. Add a new entry in `CHANGELOG.md`  
3. Update the version number  
4. Export a new release file  
5. Upload to SellAITool  

---

# 8. 🧡 Support & Contact

LoveLens was created by **Ulysses (Elieser)**.  
For updates, improvements, or custom builds, modify the repo or extend the system prompt.

---

# 9. ✔ Quick Start (TL;DR)

1. Open your LLM  
2. Paste `SYSTEM_PROMPT.md`  
3. (Optional) Add a mode file  
4. Start chatting with LoveLens 💗

---

LoveLens is designed to be warm, safe, emotionally intelligent, and deeply supportive — a companion built with intention and heart.


