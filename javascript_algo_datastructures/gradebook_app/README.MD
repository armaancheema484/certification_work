# 🎓 Student Grade Calculator

This JavaScript program calculates a students grade based on their score and determines whether they passed or failed. It also computes the class average from a list of scores.

## 🚀 Features
- ✅ Calculates the **class average**.
- ✅ Assigns letter grades (`A++`, `A`, `B`, `C`, `D`, `F`).
- ✅ Determines if a student has **passed or failed**.
- ✅ Outputs a formatted message with results.

## 🛠️ How It Works
1. **`getAverage(scores)`**  
   - Computes the **average** of all given scores.  

2. **`getGrade(score)`**  
   - Converts a numeric score into a **letter grade**:
     - `100` → **A++**
     - `90 - 99` → **A**
     - `80 - 89` → **B**
     - `70 - 79` → **C**
     - `60 - 69` → **D**
     - `< 60` → **F**

3. **`hasPassingGrade(score)`**  
   - Checks if a student **did not** receive an **F**.

4. **`studentMsg(totalScores, studentScore)`**  
   - Computes the **class average**.
   - Determines the **student's grade**.
   - Displays whether the student **passed or failed**.

## 🔧 Usage
Copy and paste the script into a .js file (e.g., grades.js).
Run the script using Node.js:
```bash
node grades.js
```

## 📌 Example Output
```bash
Class average: 71.7. Your grade: F. You failed the course.
