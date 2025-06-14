# 🌾 Crop Recommendation System Using Machine Learning

This project is a machine learning–based web application that predicts the most suitable crop to cultivate based on input parameters like soil nutrients (N, P, K), temperature, humidity, pH, and rainfall.

I explored this project to deepen my understanding of Flask-based web app development and integrating machine learning models in real-world use cases.

---

## 🚀 Features

- **Crop Prediction** using trained machine learning models  
- **User-friendly web interface** built with Flask and HTML  
- **Data preprocessing** using StandardScaler and MinMaxScaler  
- Multiple `.pkl` model files integrated into the app backend  
- Hosted locally using `Flask` for testing and iteration

---

## 🧠 What I Learned

- Deploying ML models with Flask  
- Managing virtual environments and dependencies  
- Troubleshooting template loading, file paths, and module compatibility  
- Setting up a clean GitHub repository and pushing with my own identity 😄

---

## 🔧 Technologies Used

- Python, Flask  
- scikit-learn, pandas, numpy  
- HTML/CSS  
- Jupyter Notebook (for model development)

---

## 💻 How to Run Locally

```bash
# Clone the repository
git clone https://github.com/Sania2026/crop-recommendation-ml.git
cd crop-recommendation-ml

# (Optional) Create and activate virtual environment
python -m venv venv
venv\Scripts\activate     # For Windows

# Install dependencies
pip install flask pandas scikit-learn

# Run the app
python app.py


# Key Features
Input Data Collection: The system allows users to input relevant data such as soil parameters, climate information, and geographic location.
Data Preprocessing: The input data is preprocessed to handle missing values, normalize or scale features, and transform categorical variables.
Machine Learning Models: Various machine learning algorithms are employed, including decision trees, random forests, support vector machines (SVM), and gradient boosting techniques, to build predictive models.
Model Training and Evaluation: The models are trained on historical data and evaluated using appropriate performance metrics to ensure accuracy and reliability.
Crop Recommendation: Based on the trained models, the system recommends the most suitable crops for the given input parameters.
User-Friendly Interface: The system provides a user-friendly interface where users can easily input their data, view recommendations, and explore additional information.

# Technologies Used
Python: Programming language used for model development, data preprocessing, and web application development.
Scikit-learn: Machine learning library used for model training, evaluation, and prediction.
Pandas: Data manipulation library used for data preprocessing and analysis.
NumPy: Library for numerical computing used for handling arrays and mathematical operations.
Flask: Web framework used for building the user interface and handling HTTP requests.
HTML/CSS: Markup and styling languages used for designing the web interface.
JavaScript: Scripting language used for client-side interactions and enhancing the user interface.
# Installation and Usage
Clone the repository: git clone https://github.com/your-username/crop-recommendation-system.git
Install the required dependencies: pip install -r requirements.txt
Run the application: python app.py
Access the application through the web browser at http://127.0.0.1:5000 in your browser to use the web app.
# Future Enhancements
Integration of real-time weather data to improve the accuracy of recommendations.
Incorporation of crop market prices and profitability analysis to assist farmers in making economically viable decisions.
Development of a mobile application for convenient access and usage on smartphones and tablets.
Integration of user feedback and data collection to continuously enhance the recommendation system's performance.
Contributing
Contributions to the project are welcome. If you have any suggestions, bug reports, or feature requests, please submit them through the issue tracker on the GitHub repository.



# Acknowledgements
We would like to express our gratitude to the agricultural research community, farmers, and organizations for providing valuable insights, data, and domain knowledge that contributed to the development of this Crop Recommendation System.

# Contact
Feel free to connect for ideas or collaboration: 📧 2k22.csaiml.2213001@gmail.com 📌 GitHub: github.com/Sania2026
🌱 Future Ideas
Add real-time weather data API

Deploy using Render or Railway for live access



