# Electric_Vehicle_Range_Prediction
Welcome to this project focused on predicting the driving range of electric vehicles (EVs)!
#🚗 About the Problem
Electric vehicle range—the distance an EV can travel on a full charge—is critical for consumers and manufacturers alike. This project aims to use key features like:

Battery capacity (kWh)

Vehicle efficiency (Wh/km)

Fast charging power (W)

Price (€)

Top speed (km/h)

Acceleration (0 to 100 km/h in seconds)

to predict the vehicle's range (in kilometers). Range is a continuous variable, making this a regression problem perfect for supervised machine learning.

#🎯 Why This Matters
When choosing an EV, understanding the expected driving range is vital for practical daily use and trip planning. A reliable prediction model helps manufacturers optimize design and buyers make informed decisions.

#🔍 Dataset Overview
360 EV models with 9 key attributes

Cleaned and normalized to improve model performance

Missing values handled by imputation

🛠️ Model Used
A Linear Regression model was trained on 80% of the data, tested on the remaining 20%. It achieved an excellent R² score of 0.978, showing strong predictive power.

📈 How To Use
Provide basic EV specs like battery size, efficiency, and charging power.

The model predicts expected range instantly!

🤝 Get Involved
Feel free to experiment with different ML models to improve accuracy!

Explore feature engineering or add new EV attributes for richer predictions.

Questions or suggestions? Reach out and let’s innovate!
