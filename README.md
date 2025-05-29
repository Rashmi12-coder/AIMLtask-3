# AIMLtask-3
# **Titanic Fare Prediction Using Linear Regression**  

## **Project Overview**  
This project applies **Linear Regression** to analyze and predict **fare prices** based on Titanic passenger details.  

## **Dataset Information**  
- **Dataset Used**: `cleaned_titanic.csv`  
- **Preprocessing**:  
  - Removed missing values  
  - Selected relevant features (`Pclass`, `Age`, `SibSp`, `Parch`)  
  - Target variable: `Fare`  

## **Installation & Setup**  
Run the following to install dependencies:  
```bash
pip install -r requirements.txt
```  
Or manually install:  
```python
pip install pandas numpy scikit-learn matplotlib
```

## **How to Run**  
Execute the script using:  
```python
python titanic_regression.py
```

## **Model Details**  
- **Algorithm Used**: Linear Regression  
- **Independent Variables**: `Pclass`, `Age`, `SibSp`, `Parch`  
- **Dependent Variable**: `Fare`  
- **Evaluation Metrics**: MAE, MSE, R² Score  

## **Results**  
| Metric  | Value |
|---------|-------|
| MAE     | X.XX  |
| MSE     | X.XX  |
| R² Score| X.XX  |

## **Visualization**  
Example scatter plot comparing **Age vs Fare predictions**:  



## **Project Structure**  
```
├── cleaned_titanic.csv   # Preprocessed dataset
├── titanic_regression.py # Main regression script
├── requirements.txt      # Dependencies
├── README.md             # Documentation
```

