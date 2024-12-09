# Life Expectancy Prediction Model

Analytica's Life Expectancy Prediction Model

## Features
  
- **Feature Engineering**:
  - Scaling of input data using MinMaxScaler, RobustScaler, and StandardScaler.
  - Logarithmic transformations for features like GDP and HIV incidence.

- **Prediction Models**:
  - Two models are available:
    1. **Precise Model**: Uses detailed features for high accuracy.
    2. **Minimal Model**: Requires fewer features for quick estimations.
  - Predicts life expectancy using a linear equation:  
   $$ y = b_0 + x_1 b_1 + \dots + x_n b_n $$

- **Interactive Interface**:
  - Text based input interface.
  - Validation for correct numbers.



