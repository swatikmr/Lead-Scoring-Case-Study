# Lead Scoring Analysis Project

## Project Overview
This project implements a lead scoring model for an education company to identify the most promising leads likely to convert into paying customers. Using logistic regression, the model analyzes various lead characteristics to predict conversion probability and assign lead scores.

## Table of Contents
- [Installation](#installation)
- [Data Description](#data-description)
- [Project Structure](#project-structure)
- [Model Performance](#model-performance)
- [Key Findings](#key-findings)

## Installation

### Prerequisites
- Python 3.7+
- pip package manager

## Data Description
The analysis uses the 'Leads.csv' dataset containing information about potential leads, including:
- Lead source and origin
- Total visits and time spent on website
- Page views per visit
- Lead demographics
- Specialization interests
- Current occupation
- Conversion status

## Project Structure
The project follows these main steps:
1. Data Reading & Understanding
2. Data Cleaning
   - Handling missing values
   - Removing redundant columns
   - Treatment of outliers
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
   - Binary variable conversion
   - Dummy variable creation
5. Model Building
   - Train-test split
   - Feature scaling
   - Logistic regression implementation
6. Model Evaluation
   - ROC curve analysis
   - Precision-Recall metrics
   - Cutoff optimization

## Model Performance

### Training Set Metrics
- Accuracy: 78.04%
- Sensitivity: 81.71%
- Specificity: 75.78%
- Precision: 78.99%
- Recall: 64.69%

### Testing Set Metrics
- Accuracy: 78.46%
- Sensitivity: 83.10%
- Specificity: 75.43%
- Precision: 68.83%
- Recall: 83.10%

## Key Findings

### Top Converting Lead Characteristics
1. Working Professionals
2. Leads from Lead Add Form
3. Leads from Welingak Website

### Lead Scoring Implementation
- Optimal probability cutoff: 0.314
- Lead scores range from 0-100
- Conversion rate: 83.10%

### Recommendations
1. Focus marketing efforts on working professionals
2. Optimize Lead Add Form for better conversions
3. Strengthen partnership with Welingak Website
4. Prioritize leads with scores above 31.4

## Contributing
To contribute to this project:
1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

## License
This project is licensed under the MIT License - see the LICENSE file for details
