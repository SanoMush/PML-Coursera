# Practical Machine Learning - Coursera

## Author
Mustofa Husni Sanoval

## Project Overview
This project is part of the Coursera *Practical Machine Learning* course. The goal is to predict the manner in which individuals perform weightlifting exercises using accelerometer data collected from sensors placed on the belt, forearm, arm, and dumbbell. The classification target is the "classe" variable, which represents five different movement categories (A, B, C, D, or E).

## Dataset
- **Training Data:** [pml-training.csv](https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv)
- **Testing Data:** [pml-testing.csv](https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv)

These datasets originate from the *Weight Lifting Exercise Dataset* provided by PUC-Rio. More details can be found [here](http://web.archive.org/web/20161224072740/http:/groupware.les.inf.puc-rio.br/har).

## Methodology
The analysis follows these main steps:
1. **Data Preprocessing:**
   - Removal of near-zero variance predictors.
   - Removal of columns with more than 50% missing values.
   - Splitting the dataset into training and testing subsets.
   - Ensuring data consistency across sets.

2. **Model Training & Evaluation:**
   - **Decision Tree:** Used as a baseline model.
   - **Random Forest:** Selected for higher accuracy and robustness.
   - Model performance is evaluated using cross-validation and confusion matrices.

3. **Final Predictions:**
   - The best-performing model is applied to the test dataset.
   - Predictions are saved in a `predictions.txt` file for submission.

## Results
- **Decision Tree Accuracy:** Lower accuracy due to simple model structure.
- **Random Forest Accuracy:** High accuracy, selected as the final model.
- **Final Predictions:** Successfully generated for 20 test cases.

## Repository Structure
```
|-- Practical_ML_Vscode.Rmd  # R Markdown report with code and analysis
|-- Practical_ML_Vscode.html # Compiled HTML report (peer review submission)
|-- predictions.txt          # Final predictions for submission
|-- pml-training.csv         # Training dataset (not included in repo, available via link)
|-- pml-testing.csv          # Testing dataset (not included in repo, available via link)
```

## Submission Instructions
- **Peer Review:** The compiled HTML file is included for easy review.
- **Prediction Quiz:** The `predictions.txt` file contains final predictions for submission.

## Reproducibility
To reproduce the analysis, follow these steps:
1. Clone this repository.
2. Download the datasets using the links above.
3. Open `Practical_ML_Vscode.Rmd` in RStudio.
4. Run the code chunks to execute the full analysis.

## References
- *Weight Lifting Exercise Dataset*: [PUC-Rio](http://web.archive.org/web/20161224072740/http:/groupware.les.inf.puc-rio.br/har)
- *Coursera Practical Machine Learning*: [Course Link](https://www.coursera.org/learn/practical-machine-learning)

---
This project follows the guidelines for Coursera's Practical Machine Learning assignment. If you have any questions or feedback, feel free to open an issue or submit a pull request.

# Practical-Machine-Learning---Coursera
# Practical-Machine-Learning---Coursera
