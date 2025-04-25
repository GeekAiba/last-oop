# Abstraction in 3D Shape Modeling

This project demonstrates the concept of **abstraction and polymorphism** in Python using an abstract base class for 3D shapes. The code defines an abstract class `Shape3D` with concrete implementations for `Sphere`, `Cylinder`, and `Cube` classes. It randomly generates shape instances and displays their surface area and volume.

---

## 🔧 Features

- Abstract base class `Shape3D` with abstract methods:
  - `surface_area()`
  - `volume()`
- Concrete subclasses:
  - `Sphere` → Surface Area = 4πr², Volume = (4/3)πr³
  - `Cylinder` → Surface Area = 2πr(r + h), Volume = πr²h
  - `Cube` → Surface Area = 6a², Volume = a³
- Random shape generator using `random` module
- Clean, user-friendly console output

---

## 📂 Files

- `3d_shape_modeling.py`: Main Python source code file
- `README.md`: Project documentation
- `screenshots/`: Folder for screenshots
- `sample_output.txt`: File containing sample input/output from a test run

---

## ▶️ Sample Input/Output

### Input:
```bash
Enter the number of random shapes to generate: 10
```

### Output:
```bash
Shape 1: Cylinder (radius=6, height=4)
Surface Area: 377.00
Volume: 452.39
------------------------------
Shape 2: Sphere (radius=9)
Surface Area: 1017.88
Volume: 3053.63
------------------------------
Shape 3: Cube (side=5)
Surface Area: 150.00
Volume: 125.00
------------------------------
...
```

---

## 📸 Screenshots

- `screenshots/code_structure.png`: Screenshot of code
- `screenshots/sample_run.png`: Screenshot of terminal run

---

## 📌 How to Run

1. Make sure you have Python 3 installed.
2. Clone the repository:
```bash
git clone https://github.com/yourusername/3d-shape-modeling.git
cd 3d-shape-modeling
```
3. Run the program:
```bash
python3 3d_shape_modeling.py
```
4. Enter the number of random shapes to generate.

---




## ✅ Requirements Checklist

- [x] Abstract class with 2 methods
- [x] Sphere, Cylinder, Cube classes implemented
- [x] Random object generator with correct dimension ranges
- [x] Output displays shape name, surface area, and volume
- [x] GitHub-ready with README and screenshots

