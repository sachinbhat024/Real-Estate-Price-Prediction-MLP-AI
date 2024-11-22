# Real Estate Price Prediction 🏠💹  

Predicting house prices accurately is essential for real estate professionals to make smart, informed decisions in a competitive market. Correct pricing helps avoid overvaluation, which can keep properties on the market too long, and undervaluation, which can lead to financial losses. This project focuses on using machine learning models to predict house prices based on historical data, allowing professionals to make data-driven decisions and maintain a competitive edge.

The dataset contains detailed information on over 21,000 housing transactions, including features like square footage, number of bedrooms and bathrooms, year built, condition, zipcode, and waterfront views. These features provide a full picture of the factors that influence house prices, making the data highly suitable for machine learning models to accurately capture pricing trends.

Two models were tested: Linear Regression as a simple baseline, and the more advanced Multi-Layer Perceptron (MLP). While linear regression offers basic insights, the complexity of real estate data required the MLP model to capture non-linear relationships between features and prices. The MLP’s multiple hidden layers allow it to model deeper interactions, making it more effective for this task.

Several experiments were conducted to fine-tune the MLP model by adjusting its architecture and hyperparameters. These experiments explored different numbers of hidden layers and hidden nodes. Metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R² were used to evaluate performance. The best configuration featured three hidden layers (100, 180, and 20 nodes) with early stopping to prevent overfitting.

The best model (MLP 2) achieved an MAE of 53,327.65, an RMSE of 75,185.61, and an R² of 0.846, significantly outperforming the linear regression baseline, which had an MAE of 83,442.18 and an R² of 0.670. The MLP’s ability to capture complex, non-linear relationships makes it ideal for real-world application in the real estate industry. A strong correlation between true and predicted prices (0.924) further supports the model’s accuracy for predicting house prices.

## Dataset 📊  
The dataset consists of detailed information from over **21,000 housing transactions**, including:  
- **Square footage**  
- **Number of bedrooms and bathrooms**  
- **Year built**  
- **Property condition**  
- **Zipcode**  
- **Waterfront views**  

These features provide a comprehensive understanding of the factors influencing house prices, making the dataset ideal for machine learning applications.  

## Models and Approach 🚀  
Two models were explored:  
1. **Linear Regression** – A simple baseline model offering basic insights.  
2. **Multi-Layer Perceptron (MLP)** – A more advanced neural network capable of capturing non-linear relationships in the data.  

### Model Experiments 🧪  
The MLP model was fine-tuned through various experiments, adjusting:  
- The **number of hidden layers**  
- The **number of hidden nodes**  
- **Hyperparameters** like learning rate and early stopping  

Metrics such as **Mean Absolute Error (MAE)**, **Root Mean Squared Error (RMSE)**, and **R²** were used for evaluation.  

### Best Model Configuration  
The best-performing MLP model featured:  
- **Three hidden layers** with 100, 180, and 20 nodes  
- **Early stopping** to prevent overfitting  

## Results 📈  
The advanced MLP model significantly outperformed the Linear Regression baseline:  
| Metric               | Linear Regression | MLP (Best Model) |  
|-----------------------|-------------------|------------------|  
| **Mean Absolute Error (MAE)** | 83,442.18        | 53,327.65       |  
| **Root Mean Squared Error (RMSE)** | -               | 75,185.61       |  
| **R²**                | 0.670             | 0.846            |  
| **Correlation (True vs. Predicted)** | -               | 0.924            |  

The MLP model’s ability to capture complex interactions between features demonstrates its suitability for real-world applications in real estate.  

## Conclusion 🎯  
This project highlights the importance of leveraging machine learning for real estate pricing. The MLP model’s strong performance shows its potential to assist professionals in accurately pricing properties, improving decision-making, and optimizing operations in the competitive real estate industry.  
