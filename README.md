

# 🚗 Tesla Model Y Price Prediction Using Machine Learning

A Machine Learning-powered web application that predicts the estimated resale price of a Tesla Model Y based on user inputs. The project combines Machine Learning with Flask Web Development to provide real-time predictions through an interactive web interface.

---

## 📌 Project Overview

This project uses a Multiple Linear Regression (MLR) model to predict the resale value of a Tesla Model Y. Users can enter vehicle details through a web interface, and the trained model returns the estimated price instantly.

### Technologies Used

- Python
- Machine Learning
- Scikit-Learn
- Flask
- HTML5
- CSS3
- NumPy
- Pickle

---

## 🎯 Features

- ✅ Predict Tesla Model Y resale prices
- ✅ User-friendly web interface
- ✅ Machine Learning model integration
- ✅ Real-time prediction results
- ✅ Flask backend deployment
- ✅ Responsive and animated UI design

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| Pandas | Data Processing |
| NumPy | Numerical Computation |
| Scikit-Learn | Machine Learning |
| Flask | Backend Framework |
| HTML5 | Frontend Structure |
| CSS3 | Styling and Animations |
| Pickle | Model Serialization |

---

## 📂 Project Structure

```text
TeslaY-Price-Prediction/
│
├── teslay.csv
├── MLR.ipynb
├── app.py
├── MLR_Model.pkl
│
├── templates/
│   └── index.html
│
├── screenshots/
│   ├── homepage.png
│   └── prediction.png
│
└── README.md
```

---

## 📊 Machine Learning Workflow

### 1️⃣ Data Collection

The Tesla Model Y dataset was collected and stored in:

```text
teslay.csv
```

### 2️⃣ Data Preprocessing

- Data Cleaning
- Feature Selection
- Handling Missing Values
- Data Transformation

### 3️⃣ Model Training

A Multiple Linear Regression model was trained using Scikit-Learn.

```python
from sklearn.linear_model import LinearRegression

model = LinearRegression()
model.fit(X_train, y_train)
```

### 4️⃣ Model Saving

The trained model was saved using Pickle.

```python
import pickle

pickle.dump(model, open("MLR_Model.pkl", "wb"))
```

### 5️⃣ Deployment

The model was integrated into a Flask application for real-time predictions.

---

## 🌐 Application Workflow

```text
User Input
     ↓
Flask Backend
     ↓
Machine Learning Model
     ↓
Price Prediction
     ↓
Display Result
```

---

## 🚀 Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/TeslaY-Price-Prediction.git
```

### Move to Project Folder

```bash
cd TeslaY-Price-Prediction
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Flask Application

```bash
python app.py
```

---

## 📦 Requirements

Create a file named `requirements.txt`

```text
Flask
numpy
pandas
scikit-learn
pickle-mixin
```

Install requirements:

```bash
pip install -r requirements.txt
```

---

## 💻 Example Usage

### Input

```text
Year: 2025
Kilometers Driven: 15000
Color: White
```

### Output

```text
Predicted Price: ₹ 42,50,000
```

---

## 📸 Screenshots

### Home Page

```markdown
![Home Page](screenshots/homepage.png)
```

### Prediction Page

```markdown
![Prediction Result](screenshots/prediction.png)
```

---

## 📈 Future Enhancements

- Add support for multiple Tesla models
- Improve model accuracy
- Deploy on Render or Railway
- Add prediction history
- Add user authentication
- Build a responsive dashboard
- Integrate advanced ML algorithms

---

## 👩‍💻 Author

### P. Chandana

**Data Science & Generative AI Student**

Passionate about:

- Data Science
- Machine Learning
- Artificial Intelligence
- Web Development
- Generative AI

### Connect With Me

- GitHub: https://github.com/yourusername
- LinkedIn: https://linkedin.com/in/yourprofile

---

## ⭐ Support

If you found this project helpful, please give it a ⭐ on GitHub.

---

## 🏷️ GitHub Repository Description

Tesla Model Y Price Prediction Web Application using Machine Learning, Flask, Python, HTML, CSS, and Scikit-Learn.

---

## 🔖 GitHub Topics

```text
machine-learning
python
flask
data-science
scikit-learn
linear-regression
price-prediction
tesla
web-development
artificial-intelligence
```

---

### Made with ❤️ using Python, Machine Learning, and Flask
