# Task_03_Descriptive_Stats


This repository presents descriptive statistical analyses on datasets from the 2024 U.S. Presidential Election social media activity. The analysis is performed using three approaches:

- ✅ Pure Python (no third-party libraries)
- ✅ Pandas
- ✅ Polars

The goal is to compare results, performance, and usability between native Python and two powerful data libraries.

---

## 🗂 Files Included

- `pure_python_stats.ipynb` – Analysis using only Python’s built-in libraries
- `pandas_stats.ipynb` – Analysis using the Pandas library
- `polars_stats.ipynb` – Analysis using the Polars library
- 📂 Dataset Access & Paths

⚠️ The datasets are not included in this repository.

Once downloaded, place the `.csv` files in a local directory. All scripts assume the path:

If your dataset is located elsewhere, update the file paths accordingly in the code (e.g., `df = pd.read_csv("your/path/to/file.csv")`).



---

## 🚀 How to Run the Code

1. **Install Python (3.8+)**

2. **Install required libraries** (for Pandas and Polars scripts):
   ```bash
   pip install pandas polars  
