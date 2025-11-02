# EV Range Predictor

Predict how far your electric vehicle can go on a single charge – revolutionizing EV buying decisions!

# 🚀 Project Overview
Welcome to EV Range Predictor, an exciting machine learning project designed to forecast the driving range of electric vehicles (EVs) based on key specifications. In a world where EV adoption is skyrocketing, understanding a car's range is crucial for buyers worried about "range anxiety." This project uses real-world EV data to build a predictive model that empowers users to estimate travel distance using simple inputs like battery size and acceleration.

Whether you're an aspiring data scientist, EV enthusiast, or just curious about sustainable tech, this repo demonstrates a complete ML pipeline: from data exploration to model evaluation. Built with Python and scikit-learn, it's beginner-friendly yet powerful enough for real insights!

Why this matters: Range is the #1 factor in EV purchases. Our model achieves an impressive R² score of 0.978, meaning highly accurate predictions to help you choose the right ride.

# 📊 Dataset
Source: EV_cars.csv (360 entries from ev-database.org)

Key Features:

Battery (kWh): Energy capacity

Efficiency (Wh/km): Energy use per kilometer

Fast_charge (km/h): Charging speed

Price (€): Cost in Germany

Top_speed (km/h): Maximum velocity

Acceleration (0-100 km/h in seconds): Speed to 100 km/h

Target: Range (km) – The distance on a full charge

Data Prep: Missing values imputed with means; features normalized using StandardScaler for optimal model performance.

This dataset captures diverse EVs from brands like Tesla, BYD, and MG, providing a realistic snapshot of the market.

# 🎯 Problem Statement
Unique Challenge: Predict the "Range" (how far an electric vehicle can travel on a full charge) using input features such as battery size, efficiency, fast charging rate, price, top speed, and acceleration. Since "Range" is a key real-world metric impacting EV purchase decisions and is continuous, making it suitable for supervised regression.

This isn't just theory – it's a practical tool for simulating EV performance and aiding eco-friendly choices!

# 🛠️ Tech Stack
Language: Python 3.x

Libraries:

Pandas: Data loading and manipulation

Scikit-learn: Model training, scaling, and evaluation

NumPy: Numerical computations

Model: Linear Regression (simple yet effective for this linear relationship)

Environment: Jupyter Notebook or any Python IDE (e.g., VS Code, PyCharm)

No fancy hardware needed – runs on standard laptops!

# 📈 Model Performance
Training: 80% of data (288 samples)

Testing: 20% of data (72 samples)

Metrics:

Mean Squared Error (MSE): 229.56 km² (low error for range predictions)

R² Score: 0.978 (98% variance explained – outstanding accuracy!)

Insights: Battery size and efficiency dominate predictions, highlighting their real-world importance.

Visualize results with plots (add matplotlib for scatter plots of predicted vs. actual ranges).
