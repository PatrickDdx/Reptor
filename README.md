# 🦖 Reptor

**Reptor** is a desktop application that uses large language models (LLMs) to generate structured radiology reports from free-text notes.  
Currently optimized for **chest CT** reports.

---

## ✨ Features

- 🧠 **LLM-powered**: Automatically creates full radiology reports from notes using GPT-4 or Mistral.
- ⚙️ **Offline or online**:  
  - Uses **OpenAI GPT** by default.  
  - Can optionally run fully **offline** with **Mistral via Ollama** (if installed).
- 🖥️ **Desktop app**: Built with PyQt6 — no command line required.

---

## 🩻 Target Audience

Designed for **radiologists** and medical professionals who want to quickly transform notes or findings into structured, high-quality reports.

---

## 🚀 Usage

1. Launch the app (`Reptor.exe`).
2. Paste or write your notes in the input box.
3. Click **"Befund Erstellen"**.
4. Watch as the report is generated live, line by line.

---

## 🧠 Model Support

| Model     | Backend | Streaming | Requires Internet |
|-----------|---------|-----------|--------------------|
| GPT (e.g. `gpt-4`) | OpenAI  | ✅ Yes     | ✅ Yes             |
| Mistral   | Ollama  | ✅ Yes     | ❌ No              |

> ⚠️ Note: For offline mode, Ollama and Mistral must be pre-installed.

---

## 🛠️ Installation

No installation needed. Just run the bundled `.exe` file.

> ✅ No setup, no Python, no terminal.

---

## 🧪 Development Info

If you're working with the code:

- Built with `PyQt6`
- Modular agent system for easy extension
- Streaming is implemented for final output using a worker thread

---

## 📄 License

*Proprietary / internal use only*
