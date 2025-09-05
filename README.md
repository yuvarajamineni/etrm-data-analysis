# ETRM Data Analysis Assignment

## Quick Start
1. **Install Python 3.10+**.
2. Open a terminal in this folder and create a virtual env:
   ```bash
   python -m venv .venv
   .venv/Scripts/activate  # Windows
   # or
   source .venv/bin/activate  # macOS/Linux
   ```
3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
4. Create a `data/` folder and place your six input files there:
   - `etrm_trades.csv`
   - `etrm_trades.json`
   - `etrm_trades.xlsx`
   - `etrm_trades.txt`
   - `etrm_trades.html`
   - `etrm_trades.xml`

5. **Run the script**:
   ```bash
   python analysis.py
   ```

6. Check outputs:
   - Figures in `figs/`
   - `data/combined.parquet`

## What to submit
- Your updated `analysis.py` (or a Jupyter Notebook).
- Plots (5+).
- A short **Summary** (`summary.md` or PDF) with key insights.
