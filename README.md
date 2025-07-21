# Medicine Recommendation System

This project delivers an advanced **Medicine Recommendation System** that harnesses the power of **machine learning** and **big data technologies** to offer disease predictions based on user symptoms, along with tailored health guidance.

## Summary
The system is built to help users identify likely illnesses from their reported symptoms and to generate personalized advice covering medications, nutrition, exercise routines, and safety tips.

It features a web application developed with Flask, connected to a Spark-based backend for rapid predictions and scalable data handling.

## Key Capabilities
- **Disease Assessment via Symptoms**: Uses a pre-trained Random Forest Classifier to detect diseases from provided symptoms.
- **Custom Health Guidance**:
  - Detailed explanations for diagnosed conditions.
  - Medication, diet, exercise, and precaution suggestions tailored to the individual.
- **User-Centric Web Experience**: An intuitive, interactive web front end powered by Flask.
- **Scalable Data Processing**: Backend operations use Apache Spark for efficient management of large health datasets.

## Technology Stack
- **Frontend**:
  - HTML templates rendered with Jinja2 (via Flask).
- **Backend**:
  - Flask for routing and web API.
  - Apache Spark for scalable data science and processing tasks.
  - Complementary Python libraries: NumPy, Pandas, and Pickle.
- **Machine Learning**:
  - Disease prediction delivered by a Random Forest Classifier.
  - Model training and evaluation performed using PySpark's MLlib.
- **Data Sources**:
  - Datasets mapping symptoms to diseases.
  - Resources linking each condition to recommended medications, diets, safety measures, and fitness plans.
## Project Structure
```
project-directory/
|-- datasets/
|   |-- symptoms_df.csv
|   |-- precautions_df.csv
|   |-- medications.csv
|   |-- diets.csv
|   |-- description.csv
|   `-- workout_df.csv
|-- models/
|   `-- svc.pkl
|-- app.py         # Flask application
|-- model.py       # Model training script
|-- templates/
|   |-- index.html
|   |-- about.html
|   |-- contact.html
|   `-- developer.html
|-- static/        # Static assets (CSS, JS, images)
`-- README.md

# Inspired from : "https://github.com/anna123venkat/Healthcare-Recommendation-System/tree/main"
