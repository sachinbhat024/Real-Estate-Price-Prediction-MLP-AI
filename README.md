# Real Estate Price Prediction 🏠

This project focuses on using machine learning models to predict house prices based on historical data, allowing professionals to make data-driven decisions and maintain a competitive edge.

The dataset contained detailed information on over 21,000 housing transactions, including features like square footage, number of bedrooms and bathrooms, year built, condition, zipcode, and waterfront views. These features provide a full picture of the factors that influence house prices, making the data highly suitable for machine learning models to accurately capture pricing trends.

**Two models** were tested: Linear Regression as a simple baseline, and the more advanced Multi-Layer Perceptron (MLP). While linear regression offers basic insights, the complexity of real estate data required the MLP model to capture non-linear relationships between features and prices. The MLP’s multiple hidden layers allow it to model deeper interactions, making it more effective for this task.

Several experiments were conducted to fine-tune the MLP model by adjusting its architecture and hyperparameters. These experiments explored different numbers of hidden layers and hidden nodes. Metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R² were used to evaluate performance. The best configuration featured three hidden layers (100, 180, and 20 nodes) with early stopping to prevent overfitting.

The **best** model (MLP 2) achieved an **MAE** of 53,327.65, an **RMSE** of 75,185.61, and an **R²** of 0.846, significantly outperforming the linear regression baseline, which had an MAE of 83,442.18 and an R² of 0.670. The MLP’s ability to capture complex, non-linear relationships makes it ideal for real-world application in the real estate industry. A strong correlation between true and predicted prices (0.924) further supports the model’s accuracy for predicting house prices.
