## Heorhi Halavach

Computer Science student in Kielce, Poland. I build systems that talk to people and refuse to
guess — LLM applications where every protection actually blocks instead of merely logging, and
backends whose tests can genuinely fail.

---

[![AICONIC — the admin window: messengers, the feed, one conversation, a confirmed booking](https://raw.githubusercontent.com/HeorhiHalavach/aiconic-telegram-concierge/master/docs/screens/walkthrough.gif)](https://github.com/HeorhiHalavach/aiconic-telegram-concierge)

---

### What I am building now

**[AICONIC](https://github.com/HeorhiHalavach/aiconic-telegram-concierge)** — a Telegram front
desk for a massage salon. It answers clients as the salon, books them into real free slots,
reminds them before the visit, and hands the conversation to a human the moment it touches
something it must not decide alone: health, money, a cancellation.

The interesting part is not the model, it is the layer around it. The LLM sits behind a
one-method interface (Cerebras `gpt-oss-120b` today, Claude Haiku 4.5 as the production
choice), answers under a **strict JSON schema** rather than in free text, and never performs
an action — it returns a structure that guarded code decides whether to execute.
**505 tests, 132 of 132 mutations caught**: every guard has a mutation proving the test that
protects it can turn red.

---

### Projects

| Project | What it is | Built with |
|---|---|---|
| **[AICONIC](https://github.com/HeorhiHalavach/aiconic-telegram-concierge)** | A Telegram concierge that cannot invent a price, plus an admin window that shows every messenger in one feed | Python · Telethon · LLM under a JSON schema · FastAPI · pytest |
| **[The Data Refinery](https://github.com/HeorhiHalavach/the-data-refinery-hackathon)** | A gateway that turns untrusted documents and images into clean JSON: blocks PDF/SVG payloads, strips EXIF, neutralises CSV injection, redacts PII | FastAPI · React · Docker |
| **[Nawigator Umysłu](https://github.com/HeorhiHalavach/hackathon-AI)** | A mood journal where an external LLM analyses your entries but never sees your name, e-mail or city — text is masked locally first | FastAPI · React · spaCy · Bielik LLM |
| **[Księgarnia](https://github.com/HeorhiHalavach/Ksiegarnia)** | An online bookshop assembled from parts, not from a framework: hand-written models, session auth, admin panel, 68 tests | Express · MySQL · EJS · Jest |

Also on the profile: an [Arkanoid in plain C11](https://github.com/HeorhiHalavach/PP2-Projekt)
with raylib, and a [semester planner in C++17](https://github.com/HeorhiHalavach/PO1-Projekt)
built around one abstract class and five concrete types.

---

### How I work

- **A guard blocks; a report only logs.** If a protection can be ignored, it is not a
  protection — so every rule that matters refuses the action instead of writing a warning.
- **A green test is worth nothing until it can fail.** I break the guarded line on purpose,
  watch the test turn red, then put it back. If it stays green, the test was theatre.
- **Probe before building.** A hypothesis gets checked with the shortest live experiment
  first; tests are written only around what the probe confirmed. Half of what I would have
  built carefully turned out to be unnecessary.
- **Honest limits in the README.** Every project of mine ends with what it does *not* do.

---

### Stack

**Languages** Python · JavaScript · C++ · C · SQL
**Backend** FastAPI · Express · SQLAlchemy · hand-written SQL with prepared statements
**Frontend** React · Vite · EJS · Tailwind
**Testing** pytest · Jest · supertest · mutation testing
**Tools** Docker · Git · Linux · Doxygen · premake5 · wxWidgets

**Languages I work in:** Russian, Polish, English.

---

### Contact

📫 **halavachheorhi@gmail.com** — open to freelance work in AI automation and backend.
