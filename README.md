Energy Prediction Using ANN


Problem Statement:


Predict the energy output (PE) of a power plant using environmental features: ambient temperature (AT), exhaust vacuum (V), ambient pressure (AP), and relative humidity (RH). The goal is to understand how these factors influence energy production using historical data.



Approach & Evaluation:


•	Model: Artificial Neural Network (ANN)

•	Hidden Layers/Neurons: 1–2 layers, 6–7 neurons, ReLU activation

•	Output: 1 neuron, ReLU activation

•	Metrics: MSE, R² Score

•	The ANN effectively captures the relationship between inputs and energy output, minimizing prediction error.



Dataset & Tools:

•	Dataset: Combined Cycle Power Plant dataset (energy.csv)

•	Features: AT, V, AP, RH

•	Target: PE

•	Libraries: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Keras/TensorFlow



Preprocessing & EDA:

•	Checked for missing values and outliers

•	Explored distributions, correlations, and scatter plots

•	Scaled features using StandardScaler

•	Train-test split (80/20)



Conclusion :

The ANN model predicts energy output with high accuracy, achieving low MSE and high R² on the test set, and generalizes well across the data. It can assist in forecasting power plant energy output effectively. Future improvements could include using deeper networks, ensemble models, or deploying the model for real-time applications.

