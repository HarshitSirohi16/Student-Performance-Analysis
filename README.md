# Student Performance Prediction System

A web-based student performance prediction system that uses machine learning to analyze academic and behavioral data and predict student success or failure. The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, predictive modeling, role-based dashboards, PDF report generation, and personalized recommendations to help improve student performance.

## Features

- **Data Cleaning:** Cleans and prepares raw student data for analysis.
- **Exploratory Data Analysis (EDA):** Analyzes data distributions, trends, and correlations.
- **Feature Engineering:** Creates new meaningful features to improve prediction accuracy.
- **Machine Learning Prediction:** Predicts student success or failure using a trained model.
- **Random Forest Model:** Uses the Random Forest algorithm for accurate and reliable predictions.
- **Role-Based Access:** Separate dashboards for Students, Teachers, and Administrators.
- **Student Dashboard:** View personal academic records, performance statistics, and prediction results.
- **Teacher Dashboard:** Monitor class performance, identify at-risk students, and send recommendations.
- **Administrator Dashboard:** Manage users, classes, and institution-wide performance statistics.
- **PDF Report Generation:** Generate personalized reports for students, teachers, and administrators.
- **Performance Analytics:** Visualize individual and class-level performance metrics.
- **Recommendations & Alerts:** Provides personalized recommendations for students requiring improvement.
- **User Management:** Manage student, teacher, and administrator accounts.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Random Forest Classifier
- Matplotlib
- Seaborn
- Flask
- HTML5
- CSS3
- JavaScript
- Bootstrap
- SQLite / MySQL (depending on project configuration)

## Machine Learning Workflow

### Data Preparation

- Data Cleaning
- Handling Missing Values
- Data Transformation
- Data Encoding
- Feature Scaling

### Exploratory Data Analysis (EDA)

- Distribution Analysis
- Correlation Analysis
- Data Visualization
- Statistical Summary

### Feature Engineering

- Creation of new predictive features
- Feature selection
- Data transformation for improved model performance

### Model Training

Several machine learning algorithms were evaluated before selecting the best-performing model.

- Logistic Regression
- Decision Tree
- Random Forest
- Other Classification Models (if applicable)

### Final Model

- **Random Forest Classifier**
- High prediction accuracy
- Handles complex datasets efficiently
- Good interpretability
- Robust against overfitting

## Getting Started

### Prerequisites

- Python 3.x
- pip
- Virtual Environment (recommended)

### Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/student-performance-prediction.git
cd student-performance-prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python app.py
```

Open your browser and visit:

```
http://127.0.0.1:5000
```

## Usage

### Student

- Login securely.
- View academic profile.
- Check prediction results.
- View class statistics.
- Download personalized PDF reports.

### Teacher

- Monitor class performance.
- Identify struggling students.
- Send personalized recommendations.
- Generate class performance reports.

### Administrator

- Manage student, teacher, and class accounts.
- Access institution-wide analytics.
- Generate institutional reports.
- Monitor enrollment and academic performance.

## Project Structure

```
student-performance-prediction/
│── app.py                 # Main Flask application
│── dataset/               # Student datasets
│── models/                # Trained ML models
│── templates/             # HTML templates
│── static/                # CSS, JavaScript, Images
│── reports/               # Generated PDF reports
│── requirements.txt       # Project dependencies
│── README.md              # Project documentation
```

## Application Modules

### Data Processing

Handles data cleaning, preprocessing, and feature engineering.

### Machine Learning Module

Trains and predicts student performance using the Random Forest model.

### Student Portal

Provides prediction results, academic insights, and downloadable reports.

### Teacher Portal

Displays class analytics, identifies at-risk students, and enables personalized recommendations.

### Administrator Panel

Manages users, classes, and institution-wide statistics.

### Report Generator

Creates detailed PDF reports for students, teachers, and administrators.

## Future Improvements

- Deep Learning Models
- Real-time Performance Monitoring
- Email Notifications
- SMS Alerts
- Cloud Database Integration
- Attendance Integration
- Mobile Application
- Learning Recommendation System
- Interactive Performance Dashboard

## Author

**Harshit Sirohi**  
B.Tech CSE (AI & ML)

## License

This project is intended for educational purposes and personal learning.
