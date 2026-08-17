# NumPy Practice Notebook — Day 6 📊

A comprehensive Jupyter Notebook demonstrating NumPy fundamentals for numerical data analysis. Covers array creation, manipulation, indexing, broadcasting, and aggregate functions with executed examples.

## Topics Covered

| Section | Concepts |
|---------|----------|
| 1–3 | 1D, 2D, 3D array creation & properties (`ndim`, `shape`, `size`, `dtype`) |
| 4 | Indexing & slicing (1D & 2D) |
| 5 | Reshaping with `reshape()` |
| 6 | Array generation: `zeros()`, `ones()`, `arange()`, `linspace()` |
| 7 | Mathematical operations (vectorized) |
| 8 | Vectorized operations on arrays |
| 9 | Boolean masking & filtering |
| 10 | Broadcasting mechanics |
| 11–12 | Aggregate functions: `sum`, `mean`, `min`, `max`, `median` (1D & 2D) |
| 13 | Combined analysis example |
| 14 | Key observations & conclusion |

## Tech Stack

- **Language**: Python 3.x
- **Environment**: Jupyter Notebook / Google Colab
- **Libraries**: `numpy`

## Installation

```bash
git clone https://github.com/sarathirajanhere/idra_6.git
cd idra_6
```

## Usage

### Option 1: Jupyter Notebook (Local)
```bash
pip install jupyter numpy
jupyter notebook Day6_NumPy_Practice_Notebook.ipynb
```

### Option 2: Google Colab (Recommended)
1. Open [colab.research.google.com](https://colab.research.google.com)
2. Upload `Day6_NumPy_Practice_Notebook.ipynb`
3. Run all cells

## File Structure

```
idra_6/
├── Day6_NumPy_Practice_Notebook.ipynb    # Main notebook
└── README.md                             # This file
```

## Key Learning Outcomes

- Understanding array dimensions and shapes
- Efficient numerical computing without explicit loops
- Boolean masking for data filtering
- Broadcasting rules for mixed-shape operations
- Axis-aware aggregations on 2D arrays

## Sample Output

```python
# Broadcasting example
matrix = [[10,20,30], [40,50,60]]
row_values = [1,2,3]
matrix + row_values
# Result: [[11,22,33], [41,52,63]]
```

## Notebook Preview

The notebook contains 28 cells (markdown + code) with executed outputs showing:
- Array creation and inspection
- Indexing/slicing demonstrations
- Mathematical operations with visual results
- Boolean masking filtering examples
- Broadcasting with 2D arrays
- Aggregate functions on 1D and 2D data
- Combined student marks analysis

---

*Part of the IDRA learning series — progressive data science curriculum (Day 6 of 11).*