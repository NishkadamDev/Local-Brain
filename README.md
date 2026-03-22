# 🧠 Local-Brain

> A fully offline AI brain running on a Raspberry Pi 5 — no internet, no API, no cloud. Just pure local intelligence.

---

## 🧠 About This Project

**Local-Brain** is a local AI assistant that runs entirely on a Raspberry Pi 5 using Ollama. No API calls. No Wi-Fi required. The model lives on the device and answers questions in real time — proving that you don't need the cloud to run a powerful AI.

### Real Output Example

Asked to explain why the sky is blue to a 5 year old:

> *"So, you know how we can see colors, right? Like, some colors are bright and pretty, and others are a little bit dull. When sunlight comes from the sun, it's made up of all different kinds of colors, like red, green, blue, and yellow..."*
>
> *"Isn't that magic?"*

The Local Brain types so many words per second and knows so much. 🤯

---

## 🛠️ Tech Stack

| Layer | Tool |
|---|---|
| **Hardware** | Raspberry Pi 5 |
| **Local AI Runtime** | Ollama |
| **Model** | Llama / Gemma |
| **AI Assist** | Claude (Anthropic), Gemini (Google) |
| **Language** | Python |

---

## ⚙️ How It Works

1. **Ollama runs on the Pi** — the model is downloaded and served locally, no internet needed
2. **Python sends a prompt** — a script passes the question to the local model via Ollama's API
3. **Model responds** — Llama/Gemma generates a full answer entirely on-device
4. **Output is printed** — the response streams back to the terminal in real time

---

## 🌐 Why Local AI Matters

| | Cloud AI (Claude, Gemini) | Local AI (Local-Brain) |
|---|---|---|
| **Internet required** | ✅ Yes | ❌ No |
| **Privacy** | Data leaves device | Stays on device |
| **Speed** | Fast | Depends on hardware |
| **Cost** | API credits | Free after setup |
| **Works offline** | ❌ No | ✅ Yes |

---

## 💡 Key Learnings

- Installing and running Ollama on Raspberry Pi hardware
- Understanding the difference between cloud AI and edge AI
- Serving a local LLM and querying it via Python
- The tradeoffs between local and cloud AI models

---

## 🚀 Part of the AI Bootcamp

This project was built during the **Week 2 Physical AI** phase of a 15-day AI Developer Bootcamp.  
See the full bootcamp repo → [The AI Bootcamp](../README.md)

---

*No Wi-Fi. No API key. No problem.* 📡❌
