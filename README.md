# 🦆 Duckling Search Engine

![Version](https://img.shields.io/badge/Version-0.1.0-blue) ![Built With](https://img.shields.io/badge/Built%20With-FastAPI-brightgreen) ![License](https://img.shields.io/badge/License-MIT-yellow)

---
### 🚀 Deployments

| Type             | Link                                                                                                      |
| ---------------- | --------------------------------------------------------------------------------------------------------- |
| 🌐 Live App      | [duckling-search-engine.onrender.com](https://duckling-search-engine.onrender.com/)                       |
| 📘 Documentation | [a-jean-andreasian.github.io/duckling.github.io](https://a-jean-andreasian.github.io/duckling.github.io/) |

---
## ✨ Features

### 🔒 **Secure Access**

* Session-based access
* Rate limiting to prevent abuse

### 🧠 **Banned Words Filtering**

* Custom blacklist (e.g. violence, drugs, illegal topics)
* Integrated [better_profanity](https://pypi.org/project/better-profanity/) for extra filtering


### 🖼️ **Beautiful Frontend (TailwindCSS)**

* Clean, responsive UI with Tailwind
* Live result updates with minimal JS
* Search form includes error handling

### 🔍 **Hybrid Data Retrieval**

* Uses local data, crawlers, and third-party APIs
* Stores user queries to build a private dataset
* Goal: become a self-sustaining, autonomous search engine

---

## 🔐 Banned Words

Your utils.py includes a curated list of blocked terms (weapons, drugs, scams, adult content, etc). Use is_banned(query) to enforce it in backend logic.

---
## 💻 Frontend Preview

![Screenshot](https://i.ibb.co/DDkJgDRd/Untisstled.png)

---

## 👨‍💻 Author

Made by **Armen-Jean Andreasian**, a backend developer who prefers real work over LinkedIn fluff.
