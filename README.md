# 🎓 EducationPerfectedAgain

**Automatic answer bot for Education Perfect language tasks using Puppeteer + Electron**

<p align="center">
  <img src="result.png" alt="Bot Screenshot" />
</p>

---

## 📘 Overview

**EducationPerfected** automates translation and listening tasks on [Education Perfect](https://www.educationperfect.com/).

- ✅ Auto login via a simple UI  
- ✅ Saves your credentials (optional delete button)  
- ✅ Launches a minimisable control panel inside the task window top bar  
- ✅ Supports text + audio questions  
- ✅ Learns from mistakes in real-time  

### Available Modes:
- ⚡ **Instant** – answers and submits immediately  
- ⏸️ **Semi-Auto** – waits for you to hit Enter  
- ⏱️ **Delayed** – default mode, submits after a short delay  

---

## 🛠 Getting Started

**Download the latest `.zip` for your platform from the [Releases page](https://github.com/AndreNijman/EducationPerfectedAgain/releases).**
1. MAKE SURE LATEST VERSION OF node.js IS INSTALLED  
2. Extract the ZIP  
3. Open the folder  
4. **Run `install.cmd` once** to install Puppeteer (requires internet)  
5. Run `EducationPerfectedBot.exe`  
6. Enter your login and click **Start**

Chrome will open automatically and start the bot.

---

## ⚠️ Windows Defender / Antivirus

Since this app is unsigned, Windows SmartScreen or your antivirus **might block it**.

If that happens:
- Click **More info** → **Run anyway**
- Allow it in your antivirus or security software

---

## 🧭 Control Panel Guide

Once inside a task, a floating panel appears:

| Icon  | Function              |
|-------|------------------------|
| 🔄    | **Refresh** — reloads word list and audio map *(wait for popup)*  
| ▶️    | **Start/Stop** — toggles bot activity  
| ⚡    | Instant — submit instantly  
| ⏸️    | Semi-Auto — wait for Enter  
| ⏱️    | Delayed — submit after a short delay  

---

## 🧑‍💻 Development

```bash
npm install
npm run package
```

The EXE will be built into a folder called `EducationPerfectedBot`.

---

## 📝 Notes

- Your login is saved locally unless deleted  
- UI closes when the bot starts  
- Chrome runs maximized and visible  
- After clicking **Refresh**, wait for confirmation before using the bot  
- Puppeteer is required and gets installed with `install.cmd`  
- **If the bot starts getting listening questions wrong repeatedly, try clicking 🔄 Refresh again to reload the latest audio mappings**
  
---

**Author:** André Nijman


---

## ⚖️ Disclaimer

This project is provided for **educational purposes only** — to demonstrate and explore how tools like **Electron**, **Puppeteer**, and **Node.js** can be used to automate browser tasks, build desktop apps, and document technical workflows.

By using this software, you agree that:

- ❌ The author (**André Nijman**) is **not responsible** for how you use this bot.  
- ❌ Any misuse, such as violating platform rules or using it dishonestly, is **your responsibility**.  
- ✅ This tool is meant for learning, testing, and teaching automation concepts only.

Use it responsibly.
