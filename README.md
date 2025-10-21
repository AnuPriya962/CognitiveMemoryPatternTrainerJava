

# 🧠 Cognitive Pattern Memory Trainer

A desktop game built with **Java Swing** that tests and strengthens your **pattern recognition and working memory** through sequences of numbers, colors, and symbols. Each correct streak makes the challenge harder — and keeps your brain on its toes.

---

## 🌟 Features

* **Interactive Gameplay:** Memorize a sequence of mixed elements — numbers, colors, and symbols — and recall them in the correct order.
* **Adaptive Difficulty:** The sequence grows as you improve. Every 3 correct rounds increases the sequence length.
* **Persistent Progress:** Your **score and high score** are saved locally, so your streak continues across sessions.
* **Smooth Visuals:** Gradient backgrounds, animated buttons, and gentle transitions for a polished experience.
* **Simple Yet Addictive:** Quick rounds with countdowns and instant feedback.

---

## 🎮 How to Play

1. Run the game (see setup below).
2. Click **“Let’s Start”** to begin.
3. A short countdown will appear, then a pattern sequence (numbers, colors, or symbols) flashes on screen.
4. Memorize it carefully — once it disappears, enter the sequence exactly as shown.
5. Click **“Check Answer”** to see if you nailed it.
6. Keep going! The longer your streak, the more challenging it gets.

---

## ⚙️ Setup

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/CognitivePatternMemoryTrainer.git
cd CognitivePatternMemoryTrainer
```

### 2. Compile

Use `javac` to compile the main Java file:

```bash
javac CognitivePatternMemoryTrainer.java
```

### 3. Run

Launch the game with:

```bash
java CognitivePatternMemoryTrainer
```

---

## 🧩 Project Structure

```
CognitivePatternMemoryTrainer.java
Coddex.ttf                 # (optional custom font)
README.md
```

The project is self-contained — all UI, logic, and persistence are in one file.
If `Coddex.ttf` exists in the same directory, it will be automatically used for styling.

---

## 💾 Save File

Your progress is automatically saved in:

```
/home/<user>/.cognitive_trainer_save
```

You can delete this file anytime to reset your score.

---

## 🧠 Future Ideas

* Sound and visual feedback for sequences
* Multiple difficulty modes
* User profiles
* Leaderboard and cloud save

---

## 🛠️ Technologies Used

* **Java Swing** for UI
* **AWT Graphics2D** for custom gradients and effects
* **Serialization** for saving player progress

---

## 👨‍💻 Author

**Anu**
CSE Engineer | Writer | Curious Mind

> “Patterns are the poetry of logic — train your memory to read between the lines.”

