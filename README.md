# MSCI151_CW5_Dewi
This repository contains the Google Colab file `CW5_Dewi.ipynb`, which implements a mixed-integer linear programming (MILP) model for the Java & Co. barista scheduling problem for the Coursework 5 submission. 

The notebook builds:
- A **Baseline Model** (Part A)
- A **Fairness Model** (Part B)
- A **Skills Variant** 
- Several **Sensitivity Analysis** (Closing at 19:00, Part-Time Min Hours, Wage ±10%, and One-Day Unavailability)

All models are implemented in Python using **PuLP** and the **CBC** solver.

---

## Requirements
This notebook can be run in **Google Colab**.

Python packages required:
- `pulp`
- `pandas`
- `numpy`
- `tabulate`
- `matplotlib`
- `seaborn`

## How to Access The ipynb File
- Open Google Colab (https://colab.research.google.com/).
- Click the "Upload" button on the welcome screen.
- Select the downloaded `CW5_Dewi.ipynb` file from local computer using the file explorer.
- The file can then be opened in a new notebook tab, allowing access to its contents.
- Click the 'Run all' button to execute all cells in order.
- Wait for all the cells to run.
- Scroll through each of the section until the end.
- The notebook prints status, total cost, weekly hours per barista, and a schedule table for each scenario. Some results are plotted (cost comparison, wage sensitivity).
