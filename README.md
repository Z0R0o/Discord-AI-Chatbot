<!-- Dark Themed Header -->
<p align="center">
  <img src="https://github.com/user-attachments/assets/66c67b28-1165-4a54-bdf3-17ce50e6d679" alt="banner" width="100%" />
</p>

<h1 align="center" style="color:white;">🧠 Discord AI Assistant</h1>
<p align="center">
  <b><i>Minimal AI bot that remembers you.</i></b><br>
  Built using <code>Mistral-7B</code> + <code>OpenRouter</code> with clean memory and zero commands.
</p>

---

## 🪐 Features

- 🧠 <b>Remembers what you say</b> — conversation memory per user
- 💬 <b>Talk by @mentioning</b> — no prefix, no clutter
- 🧾 <b>Pure JSON memory</b> — no DB, no bloat
- ✨ <b>Minimal, beautiful, expandable</b> design

---

## 🖼️ Sneak Peek

> 🗂 **Clean Memory System**  
Stores memory in per-user JSON files, automatically.

<p align="center">
  <img src="https://github.com/user-attachments/assets/d319fae1-7bcd-4fb9-90b0-baab052a4c26" width="80%" />
</p>

> 🧠 **AI Response Test**  
Short and smart — no overkill, just brains.

<p align="center">
  <img src="https://github.com/user-attachments/assets/b81c7fd1-4ee4-4298-af96-05f4a635b438" width="80%" />
</p>

---

## 🧩 Structure

```bash
📁 ai-assistant/
│
├── ai.py          # Handles OpenRouter API calls
├── memory.py      # Loads / Saves user memory
└── bot.py         # Discord bot logic
