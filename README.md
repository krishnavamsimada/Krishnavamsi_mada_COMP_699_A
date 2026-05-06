# HouseBroker – House Price Recommendation System

HouseBroker is a machine learning–based house price recommendation and evaluation system developed as part of the COMP-699-A Professional Seminar course. The project applies predictive analytics and regression modeling to estimate property prices based on housing attributes such as location, number of rooms, accessibility, and proximity to amenities.

The system provides:
- Predicted house price
- Recommended price range
- Pricing classification (Underpriced, Fairly Priced, Overpriced)
- Feature importance analysis

---

# Project Objective

The goal of this project is to demonstrate the practical implementation of:
- Predictive analytics
- Regression modeling
- Object-oriented system design
- UML-based system analysis
- Data preprocessing and evaluation workflows

This project focuses on applying concepts learned in coursework rather than building a commercial real estate platform.

---

# Technologies Used

- Python 3
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn

---

# Machine Learning Model

The system uses:
- Linear Regression
- Feature Scaling using StandardScaler
- RMSE and R² evaluation metrics

Dataset used:
- California Housing Dataset (Scikit-learn)

---

# Core Features

## End User Features
- Enter housing/property attributes
- Receive predicted property price
- View recommended price interval
- Compare listing price with predicted price
- View pricing classification
- Understand influential features affecting prediction

## Administrative Features
- Upload datasets
- Train regression models
- Evaluate model performance
- Activate prediction models

---

# System Workflow

```text
Input Data
   ↓
Input Validation & Preprocessing
   ↓
Feature Scaling
   ↓
Regression Model Prediction
   ↓
Price Interval Calculation
   ↓
Pricing Classification
   ↓
Feature Importance Analysis
   ↓
Prediction Results
```

---

# Project Structure

```text
Krishnavamsi_mada_COMP_699_A/
│
├── HouseBroker_CaliforniaDataset_SCode.ipynb
├── HouseBroker- Final paper.docx
├── README.md
```

---

# Installation

## Clone Repository

```bash
git clone https://github.com/<your-username>/Krishnavamsi_mada_COMP_699_A.git
```

## Navigate to Project Folder

```bash
cd Krishnavamsi_mada_COMP_699_A
```

## Install Required Libraries

```bash
pip install numpy pandas scikit-learn jupyter
```

---

# Running the Project

## Start Jupyter Notebook

```bash
jupyter notebook
```

## Open Notebook

Open:

```text
HouseBroker_CaliforniaDataset_SCode.ipynb
```

## Run All Cells

Execute notebook cells sequentially to:
- Load dataset
- Train model
- Generate predictions
- Perform evaluation
- Run unit and integration tests

---

# Example Output

```text
Predicted Price: 2.34
Price Range: (1.90, 2.78)
Classification: Fairly Priced

Top Influential Features:
- MedInc
- AveRooms
- Latitude
- Longitude
- HouseAge
```

---

# Testing

## Unit Testing
The project includes unit tests for:
- Input preprocessing
- Prediction generation
- Interval calculation
- Classification logic
- Feature importance
- Full prediction pipeline

## Integration Testing
Integration tests validate:
- End-to-end workflow
- Data flow consistency
- Classification integration
- Feature importance integration

---

# UML and System Design

The project includes:
- Use Case Diagram
- Activity Diagram
- Sequence Diagram
- Package Diagram
- Class Diagram
- Object Diagram

---

# Performance Metrics

The system evaluates model performance using:
- RMSE (Root Mean Squared Error)
- R² Score

---

# Limitations

- Prediction quality depends on dataset quality
- Sudden market fluctuations are not captured
- The system provides estimation guidance only
- Not intended for financial or legal decision-making

---

# Future Enhancements

- Web-based frontend deployment
- Multiple regression model support
- Advanced ensemble models
- Real-time market integration
- Persistent database storage
- User authentication system

---

# Academic Context

This project was developed for:

```text
COMP-699-A Professional Seminar
Spring 2026
```

---

# References

1. Dennis, A., Wixom, B., & Tegarden, D. (2020).  
   *Systems Analysis and Design: An Object-Oriented Approach with UML (6th ed.)*. Wiley.

2. Géron, A. (2022).  
   *Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow (3rd ed.)*. O’Reilly Media.

---

# Author

## Krishna Vamshi Mada

Graduate Student  
Professional Seminar Project  
Spring 2026

---

# Repository Contents

- Source Code Notebook
- Final Project Paper
- UML-Based System Design
- Unit Tests
- Integration Tests
- Documentation
