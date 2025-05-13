
# AI Agents Assignment

This repository contains the implementation of four different AI agents designed for various environments and problems. Each question showcases a different type of intelligent agent and applies relevant AI principles and search techniques.

---

## 🩺 Question 1: Medical Diagnosis System Using a Simple Reflex Agent

**Marks: 20**

### 📌 Problem Statement
Develop a Medical Diagnosis System that functions as a **Simple Reflex Agent**, diagnosing diseases based on user-provided symptoms and test reports.

### ✅ Features
- User inputs symptoms and test results.
- System matches inputs against predefined medical conditions.
- Displays diagnosed disease and suggested treatment.

### 🦠 Diagnosable Diseases
- **Acute Appendicitis**: Symptoms: Fever, Abdomen Pain, Vomiting; Test: High TLC, Neutrophils, ESR.
- **Pneumonia**: Symptoms: Fever, Cough with Sputum, Chest Pain; Test: High TLC, Neutrophils, ESR; Chest X-ray shows pneumonic patch.
- **Acute Tonsillitis**: Symptoms: Fever, Cough; Test: Red Tonsils with Pus.

### 💊 Treatments
- Surgery, Antibiotics, Anti-allergic + Paracetamol (as per disease).

---

## 🕳️ Question 2: Model-Based Agent for the Wumpus World

**Marks: 20**

### 📌 Problem Statement
Create a model-based agent to navigate the deterministic and partially observable **Wumpus World**.

### ✅ Features
- Grid-based environment representation.
- Agent can detect pits, Wumpus, gold, and empty blocks.
- Uses percepts to update internal world state.

### 🎯 Goal
- Find the gold.
- Return safely to the starting position.

### ⚙️ Actions
- Grab gold, Move (up/down/left/right), Do nothing.

### 📤 Output
- Current position of the agent.
- Updated state of the world.
- Prompt user after each move for better visibility.

---

## 👾 Question 3: Pacman Game Agent

**Marks: 20**

### 📌 Problem Statement
Design a **Goal-Based or Utility-Based Agent** to play Pacman in a 4×4 grid environment.

### ✅ Features
- Avoids ghosts unless powered by a cherry.
- Consumes all food and power pellets.
- Updates grid state and prints after each move.

### 🎯 Agent Goals
- Maximize pellet consumption.
- Avoid being destroyed by ghosts.

### ⚙️ Movement
- Up, Down, Left, Right.

### 📤 Output
- Grid state, Pacman position, Remaining pellets, Utility score (if applicable).

---

## 🤖 Question 4: Room Service Robot

**Marks: 20**

### 📌 Problem Statement
Develop a robot to serve rooms A, B, and C from a service room using search strategies.

### ✅ Features
- Robot can only serve one room at a time.
- Must return to service room after each service.
- Each room served exactly once.

### 📍 Algorithms Implemented
- Depth First Search (DFS)
- Iterative Deepening DFS (IDDFS)

### ⚙️ Costs
- Move + Serve (Left/Right): 5
- Move + Serve (Up): 1
- Return to service room: 0

### 📤 Output
- Path followed by robot.
- Total cost of the path.

---

## 📁 Folder Structure

```
├── medical_diagnosis.py
├── wumpus_world.py
├── pacman_agent.py
├── room_service_robot.py
└── README.md
```

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/your-username/ai-agents-assignment.git
cd ai-agents-assignment

# Run any assignment file using Python
python3 medical_diagnosis.py
```

---

## 🧑‍💻 Author

Abyaz Israr — [LinkedIn](https://linkedin.com/in/abyazisrar)

---

## 📜 License

This project is licensed under the MIT License.
