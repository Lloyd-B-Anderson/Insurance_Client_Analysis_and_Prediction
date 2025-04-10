# Insurance Client Analysis and Prediction Project

## Project Overview
This project for Sure Tomorrow insurance company explores machine learning applications to solve four key business tasks:
1. Finding similar clients for targeted marketing
2. Predicting insurance benefit eligibility
3. Forecasting potential benefit amounts
4. Implementing data protection while maintaining model performance

## Key Features
- **Data Analysis**: Clean dataset with 5,000 client records (age, gender, salary, family members) and insurance benefits received
- **Machine Learning Models**: KNN, logistic regression, linear regression
- **Data Protection**: Implemented matrix multiplication for data obfuscation
- **Evaluation**: Comprehensive model testing with metrics (RMSE, F1, accuracy)

## Project Structure
1. **Data Preparation**
   - Load and clean insurance data
   - Standardize features
   - Split into training/test sets

2. **Task Solutions**
   - **Task 1**: Client similarity using KNN
   - **Task 2**: Benefit prediction with logistic regression
   - **Task 3**: Benefit amount forecasting with linear regression
   - **Task 4**: Data protection algorithm implementation

3. **Results & Conclusions**

## Key Findings
- KNN effectively identifies similar clients for marketing (Task 1)
- Logistic regression (F1=0.89) significantly outperforms dummy classifier (F1=0.15) for benefit prediction (Task 2)
- Linear regression achieves RMSE=0.34 for benefit amount forecasting (Task 3)
- Data obfuscation maintains model performance while protecting privacy (Task 4)

## Technical Highlights
- Implemented custom similarity metric (Euclidean distance)
- Compared multiple machine learning approaches
- Developed matrix-based data protection system
- Validated model robustness through comprehensive testing

The project demonstrates practical machine learning applications for insurance business needs while addressing data privacy concerns. All tasks were successfully completed with models showing strong performance.
