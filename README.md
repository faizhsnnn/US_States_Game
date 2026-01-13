# 🗺️ U.S. States Guessing Game (Python)
![Python](https://img.shields.io/badge/Python-3.x-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Challenge](https://img.shields.io/badge/Challenge-90DaysOfCode-orange)

# 📌 Overview

The U.S. States Guessing Game is an interactive Python application developed using Turtle graphics and Pandas. The application prompts users to identify all 50 U.S. states on a graphical map, reinforcing core programming concepts through a practical, data-driven approach.

This project was built as part of my #90DaysOfCode commitment and demonstrates how Python can be used to integrate data processing with simple graphical interfaces.

---
# 🚀 Key Features

🗺️ Interactive graphical interface using Turtle

⌨️ Real-time user input through dialog prompts

📊 Dynamic loading of state data from a CSV file

✍️ Accurate placement of state names using coordinates

💾 Automatic generation of states_to_learn.csv for missed states

🧠 Clean, readable, and beginner-friendly implementation

---
# 📁 Project Structure
```
us-states-game/
│
├── main.py
│   └── Core game logic and user interaction
│
├── 50_states.csv
│   └── Dataset containing U.S. state names and map coordinates
│
├── blank_states_img.gif
│   └── Background map image used for the game interface
│
└── README.md
    └── Project documentation
```

---
# 🛠️ Application Workflow

The application loads state data from a structured CSV file.

A blank U.S. map is displayed using Turtle graphics.

Users enter state names via an input dialog box.

Correct guesses are rendered on the map at precise coordinates.

Upon exit, all unguessed states are exported to states_to_learn.csv.

This mirrors a real-world data processing pipeline using user input and structured datasets.

---
# ▶️ Execution Instructions

1️⃣ Clone the Repository
```
git clone https://github.com/your-username/us-states-game.git
cd us-states-game
```
2️⃣ Run the Application
```
python main.py
```
⚠️ Important Notes

All project files must remain in the same directory.

CSV column names (state, x, y) should not be modified.

The map image file is required for correct GUI rendering.

---
# 🧠 Concepts Demonstrated

CSV data processing using Pandas

GUI development with Turtle

User input validation and control flow

List filtering and conditional logic

File creation and data export

Clean and modular code structure


---
# 🎯 Project Significance

This project serves as a transition from basic Python scripting to interactive, data-driven applications. It highlights the ability to combine logic, datasets, and visual elements—skills directly applicable to automation, scraping, and entry-level software development roles.

---
# 👨‍💻 Author

Faiz Hasan

BCA Final Year — Graphic Era University

🚀 #90DaysOfCode | Python Learner

---
*“Strong fundamentals are built by turning concepts into working applications.”*
