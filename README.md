# 🔺 Semantic Network Triangle Solver

## 📌 Overview
This project is a **Triangle Problem Solver** built using a **Semantic Network **.

The system allows users to input known triangle values (sides, angles, heights, etc.), then automatically:
- Infer missing values
- Classify triangle types
- Visualize the triangle
- Show reasoning steps and formulas

---

## 🚀 Key Features

### 🧠 1. Semantic Network Inference Engine
- Uses a rule-based system (R0 → R89)
- Automatically deduces unknown values from given inputs
- Displays inference relationships through a matrix

---

### 📊 2. Relation Matrix Visualization
- Shows connections between variables and rules
- Values:
  - `1` (green): positive relation
  - `-1` (red): negative relation
  - `0`: no relation
- Click any variable to view **detailed reasoning path**

---

### 🔺 3. Full Triangle Solver
- Supports solving with:
  - 3 sides
  - 2 sides + 1 angle
  - Heights, medians, bisectors, etc.
- Calculates:
  - Sides, angles
  - Area (S), semi-perimeter (p)
  - Heights (ha, hb, hc)
  - Medians (ma, mb, mc)
  - Bisectors (la, lb, lc)
  - Radii (R, r, ra, rb, rc)

---

### 🧩 4. Triangle Classification
Automatically detects:
- Right triangle 📐
- Acute triangle 🔷
- Obtuse triangle 🔺
- Equilateral triangle ⬡
- Isosceles triangle △
- Right isosceles triangle ◱

Includes:
- Explanation
- Mathematical justification

---

### 🎨 5. Interactive Visualization
- Draws triangle with:
  - Side labels
  - Angle values
- Optional overlays:
  - Incircle (I)
  - Circumcircle (O)
  - Heights
  - Medians
  - Angle bisectors
- Includes legend for clarity

---

### 📜 6. Step-by-Step Reasoning
- Displays full inference chain
- Shows which formulas were used (R0 → R89)
- Helps users understand how results are derived

---

### 🎯 7. Selective Calculation
- Compute only specific variables
- Useful when you don't need full solution
- Shows which values can/cannot be computed

---

### 💾 8. Export Results
- Save output to `.txt` file
- Includes:
  - Input data
  - Computed results
  - Reasoning steps

---

### 🌗 9. Dark / Light Mode
- Switch between UI themes instantly
- Dark mode optimized for long usage

---

## 🖥️ User Interface

### Sidebar (Input Panel)
- Enter:
  - Sides: `a, b, c`
  - Angles: `A, B, C`
  - Heights: `ha, hb, hc`
  - Medians: `ma, mb, mc`
  - Bisectors: `la, lb, lc`
  - Radii: `R, r, ra, rb, rc`
  - Other: `p, S`

---

### Main Tabs

#### 📊 Matrix
- Shows semantic relationships (variables vs rules)

#### 🔺 Results & Classification
- Displays all computed values
- Shows triangle type
- Includes visualization

#### 📐 Formulas
- Contains 90+ triangle formulas:
  - Area
  - Cosine law
  - Sine law
  - Heights
  - Medians
  - Special triangle rules

---

## ▶️ How to Run

### Requirements
- Python 3.8+
- numpy
- tkinter (usually built-in)

### Install dependencies
```bash
pip install numpy
