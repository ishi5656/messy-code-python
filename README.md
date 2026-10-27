
---

### 2️⃣ Repo: `messy-code-python`
🔗 **URL:** `https://github.com/ishi5656/messy-code-python`

```markdown
# Messy Python Code Improvement (AI-Assisted Refactoring)

A hands-on project demonstrating code review, modular refactoring, and AI-assisted code improvement using Cursor AI.

## Author
- **Ishika Choudhary** (Enrolment No: `25BCON1173`)
- BTech Computer Science & Engineering
- GitHub: [@ishi5656](https://github.com/ishi5656)

---

## Objectives
- Identify common code smells: cryptic variable names, code duplication (DRY violations), and poor modularity.
- Use AI assistance (Cursor AI) to analyze script behavior without altering intended outputs.
- Refactor messy procedural scripts into clean, PEP 8-compliant modular functions.
- Add input validation to prevent runtime errors like `ZeroDivisionError`.

---

## Before & After Comparison

| Metric | Original (`messy_py.py`) | Improved (`improved_py.py`) |
|---|---|---|
| **Variable Naming** | Cryptic (`s1_n`, `t1`, `a1`, `g1`) | Descriptive (`student_name`, `total_marks`, `average`) |
| **Code Structure** | Flat script with repetitive copy-pasted blocks | Reusable functions (`calculate_grade`, `process_student`) |
| **Error Handling** | None (crashes on empty lists) | Guard clauses and edge case handling |
| **Standard** | Inconsistent indentation and formatting | PEP 8 compliant with docstrings |

---

## How to Run
```bash
# Run the original script
python messy_py.py

# Run the refactored script
python improved_py.py
