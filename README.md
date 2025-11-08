
# Venture Capital Fund Performance – USA vs. Europe  
**A Theoretical and Quantitative Comparison of Venture Capital Fund Performance in the USA and Europe**

This repository contains the Jupyter notebooks and the exported tables and figures used for the empirical analysis in my Bachelor Thesis at the University of St. Gallen (HSG).  
The study compares venture capital (VC) fund performance in the United States and Europe between 2009 and 2017 using Preqin data accessed through WRDS.



## Author  
**Tonio Isenschmid**  
University of St. Gallen (HSG)  
Bachelor Thesis, 2025  
Supervisor: Prof. Dr. Tereza Tykvová  



## Abstract  
Earlier academic literature has consistently found venture capital (VC) funds in the USA to outperform their European counterparts. This thesis reassesses that claim through a theoretical and quantitative analysis. The theoretical section examines key performance drivers across regions, contrasting earlier findings with recent evidence to trace potential developments. The empirical section applies OLS regressions to 733 funds from vintages 2009–2017, assessing internal rate of return (IRR), distributions to paid-in capital (DPI), and total value to paid-in capital (TVPI), while testing the effects of industry specialization and fund size. The theoretical analysis shows that many arguments for American outperformance have lost validity: European funds now employ more general partners on average, general partner experience has risen substantially, average fund size has converged, the USA’s former dominance in early-stage investing has reversed, and there is no clear evidence for fund specialization or size as a driver of superior American performance. The empirical analysis finds that while US funds outperformed strongly across all metrics from 1993–2008, there is no difference in average fund performance from 2009–2017 in IRR and TVPI, although a reduced but remaining outperformance persists in DPI. Additionally, this thesis investigates the performance effects of fund size and industry specialization across both geographies, but no truly generalizable patterns emerge. These findings challenge conventional academic and industry assumptions by offering an updated perspective on European VC performance and its gap relative to the USA.  



## Repository Structure  
- **`code/`** – Contains the two Jupyter notebooks used for data preparation and analysis:  
  - `Data Handling.ipynb` – Preprocessing and preparation of Preqin fund-level data (merging, variable construction, winsorization).  
  - `Descriptive Statistics & Models.ipynb` – Descriptive statistics, OLS regression models (M1–M4), and generation of output tables and figures.  
- **`tables_and_figures/`** – Contains the final descriptive statistics and regression model results exported from the analysis notebooks.  



## How to Run  
1. Clone this repository.  
2. Obtain access to the **Preqin Venture Capital dataset** via **Wharton Research Data Services (WRDS)** using an institutional account (e.g., University of St. Gallen license).  
   - The notebooks cannot be executed without this dataset.  
3. Download the relevant Preqin CSV files and place them in your local working directory, following the paths expected in `code/Data Handling.ipynb`.  
4. Open the notebooks in JupyterLab or VS Code.  
5. Run the notebooks in the following order:  
   - `code/Data Handling.ipynb`  
   - `code/Descriptive Statistics & Models.ipynb`  



## Data Source  
All performance data were obtained from **Preqin**, accessed through **Wharton Research Data Services (WRDS)** under the **University of St. Gallen institutional license**.  
Due to strict licensing restrictions, the underlying Preqin dataset **cannot be shared, redistributed, or uploaded** to this repository.  



## Contact  
**Email:** tonio.isenschmid@student.unisg.ch  
