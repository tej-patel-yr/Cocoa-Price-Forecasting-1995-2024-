# Cocoa Price Forecasting (1995-2024)
Cocoa Price Forecasting (1995-2024): A Time Series Approach with Python  

<img width="551" height="291" alt="Screenshot 2025-07-18 011132" src="https://github.com/user-attachments/assets/22e5fa75-24b6-47e7-b0fa-c20457ebf397" />

## 🌟 Project Essence
This project delivers:
- A **scientific approach** to modeling cocoa price fluctuations
- **Production-ready** forecasting pipelines (SARIMA, TES)
- **Actionable insights** for agricultural economists

## 🔍 Key Questions Explored
1. **Trend Analysis**: How have cocoa prices evolved since 1995?
2. **Model Selection**: Which time series technique best captures cocoa's unique volatility?
3. **Practical Utility**: Can we reliably forecast 6-12 months ahead?

##  Methodology Deep Dive
### 🔬 Scientific Rigor
- **Data Transformation**: 
  - Achieved stationarity through **logarithmic differencing**
  - Seasonal decomposition with **STL**
## How to use

Clone the repository
git clone https://github.com/your-username/cocoa-price-forecasting.git
cd cocoa-price-forecasting
 Install dependencies
pip install -r requirements.txt

## Architecture
```mermaid
graph TD
    A[Raw Price Data] --> B[EDA & Cleaning]
    B --> C{Stationarity?}
    C -->|No| D[Log-Differencing]
    C -->|Yes| E[Model Training]
    D --> E
    E --> F[Hyperparameter Tuning]
    F --> G[Production Forecasts]

