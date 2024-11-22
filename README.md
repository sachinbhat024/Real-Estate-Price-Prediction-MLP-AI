# Real Estate Price Prediction 🏠💹  

## Executive Summary  
Predicting house prices accurately is crucial for real estate professionals to make informed, data-driven decisions in a competitive market. Proper pricing strategies prevent overvaluation, which can delay sales, and undervaluation, which can result in financial losses. This project leverages machine learning to predict house prices based on historical data, helping stakeholders maintain a competitive edge.

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
