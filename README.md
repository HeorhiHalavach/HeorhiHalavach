<h1 align="center">Heorhi Halavach</h1>

<p align="center">
  <b>Backend &amp; LLM developer</b> · Kielce, Poland<br>
  <sub>Python · FastAPI · Node.js · MySQL · React · C++ · Docker</sub>
</p>

<p align="center">
  <a href="mailto:halavachheorhi@gmail.com"><img src="https://img.shields.io/badge/e--mail-halavachheorhi%40gmail.com-0b7285?style=flat-square" alt="e-mail"></a>
  <img src="https://img.shields.io/badge/open%20to-freelance-2b8a3e?style=flat-square" alt="open to freelance">
  <img src="https://img.shields.io/badge/languages-RU%2C%20PL%2C%20EN-495057?style=flat-square" alt="languages">
</p>

---

I build **backends and LLM integrations**: services where the model answers under a strict
schema instead of free text, where a protection blocks the action instead of logging a
warning, and where the tests can actually fail. I am comfortable across the whole path — HTTP
API, database, browser — and drop down to C and C++ when the task sits closer to the machine.

---

### What I work with

| Area | What I have actually built |
|---|---|
| **Backend** | FastAPI and Express services: routing, sessions, authentication with bcrypt, file uploads, centralised error handling, structured logging. REST APIs described with OpenAPI. |
| **LLM integration** | A provider behind a typed interface, replies constrained by a **strict JSON schema**, system prompts assembled per request from live data, two-layer escalation to a human, token quota read from response headers instead of estimated, cost kept down by knowing that the prompt is ~90% of the spend. |
| **Databases** | MySQL — schema, pagination, search, hand-written SQL with prepared statements and whitelists where a placeholder is impossible. SQLite. YAML/CSV as storage when a database would be overkill. |
| **Frontend** | React + Vite. Also single-page interfaces in plain HTML and JS, with no build step, when a toolchain would cost more than it returns. |
| **Security** | PII redaction before data leaves the machine, file-type validation by magic numbers rather than extension, CSV-injection neutralising, SVG/XSS sanitising, EXIF stripping, hardened session cookies, deny-by-default access checks. |
| **Testing** | pytest · Jest · supertest, and **mutation testing** — breaking the guarded line on purpose to prove the test turns red. 505 tests and 132 of 132 mutations caught in AICONIC; 68 tests in Księgarnia. |
| **C / C++** | C++17 with wxWidgets — a desktop GUI built on an abstract base class and five concrete types. C11 with raylib — a full game with its own build system. Makefile, premake5, Doxygen. |
| **Tooling** | Docker &amp; Compose · Nginx · Git · Linux · devbox |
| **AI as a tool** | I use AI assistants daily for exploration, review and boilerplate — and I check what comes out of them before it ships. |

---

### Projects

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/HeorhiHalavach/aiconic-telegram-concierge"><img src="https://raw.githubusercontent.com/HeorhiHalavach/aiconic-telegram-concierge/master/docs/screens/conversation.png" width="100%" alt="AICONIC admin window: client card, conversation, reply field"></a>
<b><a href="https://github.com/HeorhiHalavach/aiconic-telegram-concierge">AICONIC</a></b> — a Telegram front desk for a salon that <b>cannot invent a price</b>. Answers clients, books real free slots, sends reminders, and hands the conversation to a human the moment it must not decide alone.
<br><sub><b>Python · Telethon · LLM under a JSON schema · FastAPI · pytest</b></sub>
</td>
<td width="50%" valign="top">
<a href="https://github.com/HeorhiHalavach/the-data-refinery-hackathon"><img src="https://raw.githubusercontent.com/HeorhiHalavach/the-data-refinery-hackathon/master/docs/screens/blocked.png" width="100%" alt="The Data Refinery blocking an executable upload"></a>
<b><a href="https://github.com/HeorhiHalavach/the-data-refinery-hackathon">The Data Refinery</a></b> — a gateway that turns untrusted documents and images into clean JSON: blocks PDF and SVG payloads, strips EXIF, neutralises CSV injection, redacts PII.
<br><sub><b>FastAPI · React · Docker · pytest</b></sub>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/HeorhiHalavach/hackathon-AI"><img src="https://raw.githubusercontent.com/HeorhiHalavach/hackathon-AI/main/docs/screenshot.png" width="100%" alt="Nawigator Umyslu journal screen"></a>
<b><a href="https://github.com/HeorhiHalavach/hackathon-AI">Nawigator Umysłu</a></b> — a mood journal where an external LLM analyses your entries but never sees your name, e-mail or city: the text is masked locally first.
<br><sub><b>FastAPI · React · spaCy · Bielik LLM · edge-tts</b></sub>
</td>
<td width="50%" valign="top">
<b>Also here</b>
<br><br>
🛒 <b><a href="https://github.com/HeorhiHalavach/Ksiegarnia">Księgarnia</a></b> — an online bookshop assembled from parts, not from a framework: hand-written models, session auth, admin panel, 68 tests.
<br><sub>Express · MySQL · EJS · Jest</sub>
<br><br>
🎮 <b><a href="https://github.com/HeorhiHalavach/PP2-Projekt">Arkanoid</a></b> — a brick breaker in plain C11: 32 simultaneous balls, falling bonuses, premake5 build, Doxygen docs.
<br><sub>C11 · raylib · premake5</sub>
<br><br>
🗓 <b><a href="https://github.com/HeorhiHalavach/PO1-Projekt">Student Assistant</a></b> — a desktop semester planner: one abstract class, five concrete event types, CSV persistence that rebuilds the right subclass on load.
<br><sub>C++17 · wxWidgets · Doxygen</sub>
</td>
</tr>
</table>

---

<p align="center">
  <b>📫 halavachheorhi@gmail.com</b><br>
  <sub>Open to freelance work in backend development and LLM integration.</sub>
</p>
