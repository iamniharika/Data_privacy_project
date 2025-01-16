# Data Privacy Project

This project demonstrates techniques to detect and mitigate linkage and reidentification attacks in anonymized datasets using machine learning and privacy-preserving techniques. The primary dataset used is the **Adult dataset** from the UCI Machine Learning Repository.

## Project Overview

The project focuses on:

- **Linkage and Reidentification Attacks**: Analyzing how sensitive information can be inferred using quasi-identifiers and machine learning models.
- **Privacy-Preserving Techniques**: Implementing K-Anonymity and L-Diversity to reduce risks associated with data anonymization.
- **Machine Learning Models**: Utilizing models such as Random Forest, Isolation Forest, and Decision Trees to identify and mitigate privacy risks.

## Features

- Identification of quasi-identifiers, personal identifiers, and sensitive attributes in the dataset.
- Implementation of K-Anonymity and L-Diversity.
- Statistical inference attacks using logistic regression.
- Visualization of privacy risks through bar charts and other graphical representations.
- Comparison of machine learning models for detecting reidentification risks.

## Dataset

The **Adult dataset** contains demographic information and income categories. The attributes include:

- Age
- Workclass
- Education
- Marital Status
- Occupation
- Race
- Gender
- Native Country
- Income (sensitive attribute)

## Key Techniques

1. **Quasi-Identifiers Identification**
   - Attributes such as Age, Education, and Occupation are analyzed to identify quasi-identifiers.

2. **Privacy Measures**
   - K-Anonymity: Groups records with similar quasi-identifiers to protect privacy.
   - L-Diversity: Ensures that sensitive attributes within each group are diverse.

3. **Machine Learning Models**
   - **Random Forest**: Identifies patterns that may lead to reidentification.
   - **Isolation Forest**: Detects anomalies in the data.
   - **Decision Trees**: Visualizes potential privacy risks.

4. **Statistical Inference Attack**
   - Logistic regression is used to predict sensitive attributes based on quasi-identifiers.
   - Results are visualized using bar charts.

## Future Improvements

- Implement T-Closeness for further privacy protection.
- Explore differential privacy techniques.
- Enhance model accuracy and computational efficiency.

## Dependencies

- Python 3.8+
- pandas
- numpy
- sklearn
- matplotlib
- seaborn

Thank you for exploring this project. Contributions and suggestions are welcome!

