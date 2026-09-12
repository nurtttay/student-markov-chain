
# Student Performance — Markov Chain Analysis
 modeling student academic progression as a Markov chain.

## What it does

1. **Task 1** — Loads `Student_performance_data.csv`, inspects dimensions and selects key columns: `Absences`, `StudyTimeWeekly`, `GPA`, `GradeClass`.
2. **Task 2** — Bins the data into categorical states:
   - Attendance: High / Medium / Low
   - Study effort: Low / Medium / High
   - Final academic state (by GPA): Poor / Average / Good / Excellent
3. **Task 3** — Counts transitions between states across each student's sequence, to build a transition frequency table.
4. **Task 4** — Builds the full transition probability matrix, with Poor/Average/Good/Excellent set as absorbing (terminal) states.
5. **Task 5** — Projects the state distribution 10 steps forward from a given starting vector.

## Requirements

```
pandas
numpy
matplotlib
seaborn
```

## Usage

Place `Student_performance_data.csv` in the same folder as the notebook, then open and run `assignment3.ipynb` in Jupyter.

```bash
pip install pandas numpy matplotlib seaborn
jupyter notebook assignment3.ipynb
```
