# CISSP Mock Exam — 150 Questions

A fully self-contained, single-file HTML mock exam for the **CISSP (Certified Information Systems Security Professional)** certification. No server, no dependencies, no install — open in any browser and start practising.

![HTML](https://img.shields.io/badge/HTML-Single%20File-blue?style=flat-square)
![Questions](https://img.shields.io/badge/Questions-150-cyan?style=flat-square)
![Domains](https://img.shields.io/badge/Domains-8-violet?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

**🔗 Live Demo: [talha2k.com/projects/cissp/cissp_mock_test.html](https://talha2k.com/projects/cissp/cissp_mock_test.html)**

---

## Preview

> Dark cyber-themed exam interface with animated start screen, live timer, domain navigation, per-question explanations, and a full report card on submission.

---

## Features

- **150 questions** covering all 8 official CISSP domains (~19 per domain)
- **3-hour countdown timer** — warns at 15 min (yellow), 5 min (red), auto-submits on expiry
- **Instant feedback** — correct/wrong highlighted immediately after answering, with a written explanation per question
- **Flag for review** — mark any question to revisit before submitting
- **Dual sidebar** — jump by domain or navigate the full question grid (color-coded by status)
- **Report card** on submission:
  - Overall score and Pass / Fail verdict (70% threshold, matching real CISSP)
  - Domain-by-domain performance bars
  - Full review of every wrong answer with the correct answer and explanation
  - Printable via browser

---

## Domains Covered

| # | Domain | Questions |
|---|--------|-----------|
| 1 | Security & Risk Management | 19 |
| 2 | Asset Security | 19 |
| 3 | Security Architecture & Design | 19 |
| 4 | Communication & Network Security | 19 |
| 5 | Identity & Access Management | 19 |
| 6 | Security Assessment & Testing | 19 |
| 7 | Security Operations | 19 |
| 8 | Software Development Security | 19 |

---

## How It Works

The entire exam is a single `.html` file with vanilla HTML, CSS, and JavaScript.

- All 150 questions, answer keys, and explanations are stored in a JS array at the top of the `<script>` block
- No external API calls — works fully offline
- Timer state, answers, and flags are held in memory for the duration of the session
- The report is rendered client-side after submission

---

## Scoring

The passing threshold is **70%** (105/150), consistent with the ISC2 CISSP exam standard. The report card highlights domains below 70% in red so you know exactly where to focus your revision.

---

## Disclaimer

This is a practice tool for self-study purposes only. It is **not** affiliated with, endorsed by, or official material from ISC2. Questions are written for educational coverage of CISSP domain concepts and do not replicate actual exam content. Always use official ISC2 study materials alongside practice tools.

---

## Contributing

Pull requests welcome. If you'd like to:

- Add more questions to any domain
- Fix an incorrect answer or improve an explanation
- Add features (randomization, timed per-question, dark/light toggle)

Please open an issue first to discuss the change.

---

## License

MIT — free to use, share, and modify.
