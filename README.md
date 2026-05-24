# 🐍 stranger-have-a-look-at-my-python

> *"What are ya buyin'?"*

A collection of Python projects built while working through **Bro Code's Python Full Course** (11 hrs), culminating in a **Resident Evil 4 Merchant simulator** as a capstone project. From madlibs to OOP — every concept gets applied.

---

## 📂 Repository Structure

```
stranger-have-a-look-at-my-python/
│
├── LICENSE/
├── .gitignore/
│
├── 01_madlibs/
├── 02_calculator/
├── 03_weight_conversion/
├── 04_temperature_conversion/
├── 05_compound_interest/
├── 06_countdown_timer/
├── 07_shopping_cart/
├── 08_quiz_game/
├── 09_concession_stand/
├── 10_number_guessing_game/
├── 11_rock_paper_scissors/
├── 12_dice_roller/
├── 13_banking_program/
├── 14_slot_machine/
├── 15_encryption_program/
├── 16_hangman/
├── 17_alarm_clock/
├── 18_digital_clock/
├── 19_stopwatch/
├── 20_weather_app/
│
└── re4_merchant/          ← Capstone project
    ├── merchant.py
    ├── inventory.py
    ├── player.py
    └── README.md
```

---

## 📚 Course Projects

Projects follow Bro Code's [Python Full Course](https://www.youtube.com/watch?v=ix9cRaBkVe0), in order. Each folder contains the project file(s) and a short comment header explaining what concept it practices.

| # | Project | Concept(s) Practised |
|---|---------|----------------------|
| 01 | Madlibs Game | Variables, user input, strings |
| 02 | Calculator | Arithmetic, if statements |
| 03 | Weight Conversion | Type casting, conditionals |
| 04 | Temperature Conversion | Functions, conditionals |
| 05 | Compound Interest | While loops, math |
| 06 | Countdown Timer | For loops, `time` module |
| 07 | Shopping Cart | Lists, sets, tuples |
| 08 | Quiz Game | 2D collections, loops |
| 09 | Concession Stand | Dictionaries |
| 10 | Number Guessing Game | Random numbers, while loops |
| 11 | Rock Paper Scissors | Random, match-case |
| 12 | Dice Roller | Random, functions |
| 13 | Banking Program | Modules, scope, functions |
| 14 | Slot Machine | OOP basics |
| 15 | Encryption Program | String methods, functions |
| 16 | Hangman | OOP, file I/O |
| 17 | Alarm Clock | Dates & times, multithreading |
| 18 | Digital Clock | PyQt5 GUI |
| 19 | Stopwatch | PyQt5, multithreading |
| 20 | Weather App | API requests, PyQt5 |

---

## 🗡️ Capstone: RE4 Merchant Simulator

> *"Heh heh heh... Thank you."*

A CLI (and eventually GUI) recreation of the iconic Merchant from **Resident Evil 4**. Built to apply the full range of concepts learned across the course.

### Features
- [ ] Browse and buy weapons, upgrades, and items from the Merchant's shop
- [ ] Sell items from your inventory for Pesetas
- [ ] Weapon upgrade system (Firepower, Reload Speed, Capacity)
- [ ] Persistent save/load of player inventory via file I/O
- [ ] Merchant dialogue and ASCII art for atmosphere
- [ ] PyQt5 GUI (stretch goal)

### Concepts Applied
- **OOP** — `Merchant`, `Player`, `Weapon`, `Item` classes
- **Dictionaries** — shop inventory and player loadout
- **File I/O** — save/load game state
- **Exception handling** — invalid purchases, insufficient Pesetas
- **Modules** — split across logical files
- **PyQt5** *(stretch)* — graphical shop interface

### Running the Merchant
```bash
cd re4_merchant
python merchant.py
```

---

## 🛠️ Setup

**Requirements:** Python 3.10+

```bash
git clone https://github.com/YOUR_USERNAME/stranger-have-a-look-at-my-python.git
cd stranger-have-a-look-at-my-python

# For projects using PyQt5
pip install PyQt5

# For the weather app
pip install requests
```

No other external dependencies — most projects use the Python standard library only.

---

## 📈 Progress

- [x] Course started
- [ ] Section 1–10 complete
- [ ] Section 11–20 complete
- [ ] Section 21–30 complete
- [ ] Section 31–44 complete (OOP)
- [ ] Section 45–65 complete (files, APIs)
- [ ] Section 66–77 complete (PyQt5)
- [ ] RE4 Merchant CLI complete
- [ ] RE4 Merchant GUI complete

---

## 📄 License

This project is for personal learning purposes. RE4 characters and IP belong to Capcom.
