# 🔢 Sudoku Solver GUI (Java Swing)

A Java Swing-based desktop application that solves Sudoku puzzles using a backtracking algorithm. Users can input digits into a 9×9 grid, and the app automatically fills in the missing values while following standard Sudoku rules. Designed with a clean, spacious layout and intuitive controls for a smooth user experience.

---

## 🧩 Features

- ✅ Interactive 9×9 Sudoku grid
- ✅ Input validation for digits 1–9
- ✅ Backtracking-based solving algorithm
- ✅ "Solve" button to compute solution
- ✅ "Clear" button to reset the grid
- 🎨 Visually balanced layout with readable fonts and spacing

---

## 📸 Screenshot

<img width="1919" height="1030" alt="image" src="https://github.com/user-attachments/assets/297a67df-0187-464f-9f5f-ff4e59785da7" />

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yashika-BCA/SCT_SD_3/blob/main/SudokuSolverGUI.java

2.Compile and run the Java file:
   ```bash
   javac SudokuSolverGUI.java
   java SudokuSolverGUI

3.Using an IDE (like IntelliJ or Eclipse)
   Create a new Java project.
   Add a new class named SudokuSolverGUI.
   Paste the full code into that class.
   Click Run or Execute from the IDE toolbar.

🧠 How It Works
The app uses a recursive backtracking algorithm to solve the puzzle:
It scans the grid for empty cells.
Tries digits 1–9 in each cell.
Validates placements based on Sudoku rules.
Backtracks if a conflict is found.
Continues until the puzzle is solved or deemed unsolvable.

📦 Technologies Used
Java 8+
Java Swing (GUI Framework)

✨ Future Enhancements
🔍 Conflict highlighting
📂 Load puzzles from file
🎮 Puzzle generator with difficulty levels
🧠 Step-by-step solving animation

📄 License
This project is open-source and available under the MIT License.

🙌 Author
Yashika Sorani (Passionate about building visually polished and logically robust GUI applications.)
