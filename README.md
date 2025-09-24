# Simple Linear Regression Analysis Repository

A comprehensive collection of simple linear regression implementations using Python and scikit-learn, demonstrating practical applications across different domains including salary prediction, automotive safety, and healthcare analytics.

## Repository Overview

This repository contains four different linear regression projects, each solving real-world problems using single-feature predictive modeling:

### [Braking Distance Analysis](./Braking%20Distance.ipynb)
**Problem**: Predict vehicle braking distance based on speed
- **Dataset**: 49 observations of speed vs stopping distance
- **Correlation**: Strong positive relationship (r = 0.805)
- **Application**: Traffic safety, driver education, automotive engineering
- **Key Insight**: Every 1 mph increase in speed adds ~3.57 feet to braking distance

### [Position Salary Prediction](./Position_Salary.ipynb)
**Problem**: Predict salary based on years of experience
- **Dataset**: 30 employee records with experience and salary data
- **Correlation**: Very strong positive relationship (r = 0.978)
- **Application**: HR analytics, compensation planning, career guidance
- **Key Insight**: Strong linear relationship between experience and compensation

### [Diabetes Progression Analysis](./Diabetes.ipynb)
**Problem**: Predict diabetes progression using patient data
- **Dataset**: 442 patients with 10 physiological features
- **Features**: Age, sex, BMI, blood pressure, and 6 serum measurements
- **Application**: Healthcare analytics, disease progression monitoring
- **Approach**: Uses scikit-learn's built-in diabetes dataset

### [Diabetes Analysis - Alternative](./Diabetes-2.ipynb)
**Problem**: Alternative diabetes progression analysis
- **Dataset**: Same diabetes data from TSV file format
- **Focus**: BMI-based prediction with correlation analysis
- **Correlation**: Moderate positive relationship (r = 0.586)
- **Application**: Medical research, patient risk assessment

## Technologies Used

- **Python 3.x**
- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computing
- **matplotlib** - Basic plotting and visualization
- **seaborn** - Statistical data visualization
- **scikit-learn** - Machine learning library
  - LinearRegression
  - train_test_split
  - Performance metrics (MSE, MAE, R²)

## Project Structure

```
Simple-Linear-Regression/
├── README.md                    # Project documentation
├── Braking Distance.ipynb       # Speed vs braking distance analysis
├── Position_Salary.ipynb       # Experience vs salary prediction
├── Diabetes.ipynb             # Diabetes progression (sklearn dataset)
├── Diabetes-2.ipynb           # Alternative diabetes analysis
└── data/                       # Dataset files
    ├── Salary_Data.csv         # Employee salary data
    ├── mycar.csv              # Vehicle braking data
    └── diabetes.tsv           # Diabetes dataset (TSV format)
```

## Getting Started

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Running the Notebooks
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Simple-Linear-Regression.git
   cd Simple-Linear-Regression
   ```

2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

3. Open any of the `.ipynb` files to explore the analysis

## Key Concepts Demonstrated

### Statistical Analysis
- **Correlation Analysis**: Measuring linear relationships between variables
- **Data Visualization**: Scatter plots, regression lines, correlation heatmaps
- **Residual Analysis**: Model validation and assumption checking

### Machine Learning Workflow
- **Data Loading**: CSV/TSV file handling with pandas
- **Feature Preparation**: Data extraction and preprocessing
- **Train-Test Split**: Model validation strategy
- **Model Training**: Linear regression implementation
- **Performance Evaluation**: MSE, RMSE, MAE, R² metrics

### Business Applications
- **Predictive Modeling**: Making data-driven predictions
- **Risk Assessment**: Understanding relationships for decision making
- **Performance Analysis**: Evaluating model effectiveness

## Dataset Information

| Dataset | Size | Features | Target | Correlation | Domain |
|---------|------|----------|---------|-------------|---------|
| Salary Data | 30 samples | Years Experience | Salary | 0.978 | HR/Finance |
| Braking Distance | 49 samples | Speed (mph) | Distance (ft) | 0.805 | Automotive |
| Diabetes (sklearn) | 442 samples | 10 physiological | Progression | Varies | Healthcare |
| Diabetes (TSV) | 442 samples | BMI focus | Progression | 0.586 | Healthcare |

## Learning Objectives

After exploring this repository, you'll understand:

1. **Simple Linear Regression Fundamentals**
   - Mathematical relationship: y = mx + b
   - Coefficient interpretation and significance
   - Model assumptions and limitations

2. **Data Science Workflow**
   - Exploratory data analysis (EDA)
   - Feature engineering and selection
   - Model training and validation
   - Performance evaluation and interpretation

3. **Practical Applications**
   - Real-world problem solving with regression
   - Business context and decision making
   - Model limitations and considerations

4. **Python Tools and Libraries**
   - Data manipulation with pandas
   - Visualization with matplotlib/seaborn
   - Machine learning with scikit-learn
   - Jupyter notebook best practices

## Model Performance Summary

| Project | R² Score | Key Metric | Business Value |
|---------|----------|------------|----------------|
| Braking Distance | ~0.65 | Strong correlation (0.805) | Traffic safety insights |
| Position Salary | ~0.96 | Very strong correlation (0.978) | Compensation benchmarking |
| Diabetes (sklearn) | ~0.47 | Moderate predictive power | Disease monitoring |
| Diabetes (TSV) | Varies | BMI-focused analysis | Risk factor assessment |

## Contributing

Contributions are welcome! Areas for improvement:

1. **Enhanced Documentation**: More detailed explanations and comments
2. **Advanced Models**: Multiple linear regression, polynomial features
3. **Better Validation**: Cross-validation, bootstrap analysis
4. **Extended Analysis**: Feature importance, model comparison
5. **New Datasets**: Additional real-world regression problems

## License

This project is open source and available under the [MIT License](LICENSE).

## Questions or Issues?

If you have questions about the analysis or find any issues, please:
1. Check the notebook documentation and comments
2. Review the correlation analysis and visualizations
3. Open an issue for discussion

---

**Note**: This repository is designed for educational purposes to demonstrate simple linear regression concepts and practical applications across different domains.