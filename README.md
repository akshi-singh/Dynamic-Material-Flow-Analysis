# Dynamic-Material-Flow-Analysis
Dynamic MFA of metals in South African passenger vehicles.

This repository contains the code, data, and visualizations for a research project analyzing the material flows of metals in the South African automotive sector using dynamic material flow analysis (DMFA).

## 📚 Project Description

The goal of this study is to quantify and project the stocks and flows of key metals (e.g., steel, aluminum, copper, zinc) embedded in South Africa's passenger vehicle fleet. The model evaluates how different scenarios (e.g., vehicle lightweighting, lifetime extension, electrification) affect material demand and end-of-life recovery, using stock-driven approaches and uncertainty analysis via Monte Carlo simulation.


## ⚙️ ODYM Reference
Adaptation of the ODYM module for the South African vehicle fleet.

Pauliuk, S., & Heeren, N. (2020). ODYM—An open software framework for studying dynamic material systems: Principles, implementation, and data structures. Journal of Industrial Ecology, 24(3), 446-458. https://doi.org/10.1111/jiec.12952


## 📁 Repository Structure

```
mfa-sa-vehicles/
├── data/               # Input data: vehicle registrations, material compositions, etc.
├── notebooks/          # Jupyter notebooks for analysis and model runs
├── scripts/            # Reusable Python scripts (e.g., for ODYM or MCS)
├── figures/            # Output figures like Sankey diagrams, stock curves
├── README.md           # Project overview (this file)
├── requirements.txt    # Python packages and dependencies
└── LICENSE             # Project license (e.g., MIT, CC BY)
```

---

## ⚙️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/mfa-sa-vehicles.git
   cd mfa-sa-vehicles
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the analysis in Jupyter:
   ```bash
   jupyter notebook
   ```

---

## 📦 Key Tools and Libraries

- Python 3.x
- [ODYM](https://github.com/IndEcol/ODYM/tree/master/odym) 
- NumPy, Pandas
- Matplotlib / Plotly
- OpenPyXL (for Excel data handling)
- SciPy (for Weibull fitting, MCS)

---

## 🔁 Scenarios

The model supports various future scenarios:
- **Baseline** (historical trends)
- **Vehicle Light-weighting and Composition Evolution** 
- **Lifetime Shift** (early scrappage or extended life)
- **Combined Strategy** 

---

## 📬 Contact

For questions or collaborations, please contact:  
**Akshi Singh**  
📧 akshi.zn@gmail.com
