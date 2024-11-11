# zebrafish-chemical-effects-analysis

## Overview
This project analyzes the effects of various chemicals (Be, Cr, Fe, Ni, Cu, As, Cd, Ba, Ti, Pb and U) on zebrafish behavior during light and dark phases. Using a multiple regression approach, the aim is to identify which chemicals most significantly influence zebrafish movement.

## Files
- `data/`: Contains the datasets.
- `notebooks/`: Jupyter notebooks where the regression analysis is performed.
- `src/`: Python scripts for data processing and model building.
- `results/`: Results from the regression models.

## How to Run
1. Clone the repository:  
   `git clone https://github.com/hchamikadilshan/zebrafish-chemical-effects-analysis.git`

2. Navigate to the project directory:
   `cd zebrafish-chemical-effects`

3. Install required packages:
   `pip install -r requirements.txt`

4. To run the analysis, open and run the Jupyter notebook `notebooks/regression_analysis.ipynb`.

## Dependencies
- pandas
- numpy
- matplotlib
- scikit-learn
- statsmodels
## Future Work
Further analysis will be conducted using other machine learning models to enhance the understanding of the zebrafish behavioral responses to these chemicals.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
