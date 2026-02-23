# IEEE SSCS AUSC — Task 0: Initial Task (AI Team)

## 📋 Overview

This is the initial task for the **IEEE SSCS AUSC AI Team**. It consists of two parts:

1. **Matrix Operations** — Implementing fundamental linear algebra operations from scratch in Python (no NumPy).
2. **Research Papers** — Written research pieces on the **Trapezoidal Rule** (numerical integration) and **Matrix Normalization in AI**.

---

## 📂 Project Structure

```
Task0/
├── Hello IEEE/
│   ├── Code/                # Python matrix operations
│   │   ├── main.py          # Entry point — runs all operations
│   │   ├── matsum.py        # Matrix addition
│   │   ├── matsub.py        # Matrix subtraction
│   │   ├── matmul.py        # Matrix multiplication
│   │   ├── scalarsum.py     # Scalar–matrix addition
│   │   ├── scalarsub.py     # Scalar–matrix subtraction
│   │   └── matnorm.py       # Frobenius norm
│   └── Research/
│       ├── Trapezoid Rule.pdf            # Numerical integration research
│       └── Matrix Normalization in AI.pdf # Matrix normalization research
├── Task 0 - initial Task - AI Team.pdf  # Task description
└── README.md
```

---

## 🧮 Part 1 — Matrix Operations

Pure-Python implementations of core matrix operations **without external libraries**.

| Module         | Function          | Description                                              |
| -------------- | ----------------- | -------------------------------------------------------- |
| `matsum.py`    | `matsum(A, B)`    | Element-wise addition of two matrices                    |
| `matsub.py`    | `matsub(A, B)`    | Element-wise subtraction of two matrices                 |
| `matmul.py`    | `matmul(A, B)`    | Standard matrix multiplication with dimension validation |
| `scalarsum.py` | `scalarsum(s, A)` | Add scalar `s` to every element of matrix `A`            |
| `scalarsub.py` | `scalarsub(s, A)` | Subtract scalar `s` from every element of matrix `A`     |
| `matnorm.py`   | `matnorm(A)`      | Compute the Frobenius norm of matrix `A`                 |

### ▶️ How to Run

```bash
cd "Hello IEEE/Code"
python main.py
```

### Example Output

```
==================================================
Matrix A:
[[1, 2, 3], [4, 5, 6], [7, 8, 9]]
Matrix B:
[[1, 2, 3], [4, 5, 6], [7, 8, 9]]
==================================================
Matrix Sum:
[[2, 4, 6], [8, 10, 12], [14, 16, 18]]
==================================================
Matrix Sub:
[[0, 0, 0], [0, 0, 0], [0, 0, 0]]
==================================================
Matrix Mul:
[[30, 36, 42], [66, 81, 96], [102, 126, 150]]
==================================================
Scalar Sum:
[[3, 4, 5], [6, 7, 8], [9, 10, 11]]
==================================================
Scalar Sub:
[[-1, 0, 1], [2, 3, 4], [5, 6, 7]]
==================================================
Matrix Norm:
16.881943016134134
==================================================
```

---

## 📝 Part 2 — Research Papers

Two research documents included in `Hello IEEE/Research/`:

| Paper                              | Topic                                                |
| :--------------------------------- | :--------------------------------------------------- |
| **Trapezoid Rule.pdf**             | The Trapezoidal Rule for numerical integration       |
| **Matrix Normalization in AI.pdf** | Matrix normalization techniques and their role in AI |

---

## 🛠️ Requirements

- **Python 3.x** (standard library only — no external dependencies)

---

## 👤 Author

**Abdlrhman** — IEEE SSCS AUSC, AI Team
