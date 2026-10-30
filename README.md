# SmokeCheck-AI- # Health Signal Analytics: Smoker Status Classification

This project implements a machine learning-based system to classify smoker status using health signal data. The application provides a web interface for users to input health metrics and receive predictions about smoking status.

## 🚀 Features

- Web-based interface for easy interaction
- Machine learning model for smoker status classification
- Real-time predictions
- User-friendly input form for health metrics
- Responsive design

## 📋 Prerequisites

Before running this project, make sure you have the following installed:
- Python 3.7 or higher
- pip (Python package installer)

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/Virajdeokar26/SmokeCheck-AI-.git
```

2. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

## 🏃‍♂️ Running the Application

1. Start the Flask application:
```bash
python app.py
```

2. Open your web browser and navigate to:
```
http://localhost:5000
```

## 📁 Project Structure

```
health-signal-analytics/
├── app.py              # Main Flask application
├── requirements.txt    # Project dependencies
├── model.pkl          # Trained machine learning model
├── Data/              # Dataset directory
├── Demo_Model/        # Model demonstration files
├── Notebook/          # Jupyter notebooks for analysis
├── static/            # Static files (CSS, JS, images)
└── templates/         # HTML templates
```

## 🧪 Model Details

The project uses a LightGBM classifier trained on health signal data to predict smoker status. The model is saved in `model.pkl` and can be loaded for predictions.

## 📊 Dependencies

- Flask: Web framework
- numpy: Numerical computing
- pandas: Data manipulation
- scikit-learn: Machine learning utilities
- lightgbm: Gradient boosting framework
- joblib: Model persistence
