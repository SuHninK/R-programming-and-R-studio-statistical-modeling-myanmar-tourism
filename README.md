# R programming and R studio Based Statistical Modeling and Forecasting of Myanmar Tourism & Airline Arrivals

## Project Overview
Predicting international tourist and airline arrivals is foundational for macroeconomic planning, hospitality resource allocation, and optimizing commercial airline logic. 

This project establishes a rigorous, production-ready statistical forecasting framework using Python. It cleans, structures, and processes historical tourism arrival matrices, systematically breaking them down through a standardized 5-step time-series methodology to deliver highly accurate data insights and minimize prediction errors.

---

## Tech Stack & Key Analytical Capabilities (R Engine)
* **Core Language:** R Programming (RStudio Environment)
* **Primary Data Frameworks:** `tidyverse` (`dplyr`, `tidyr`) for data structuring and manipulation.
* **Statistical Modeling & Inference:** `forecast`, `stats` (Advanced Time-Series & Holt-Winters Filter).
* **Data Visualization:** `ggplot2` for high-performance trend parsing and `forecast::Acf()` for autocorrelation plots.
* **Core Competencies:** Automated Data De-noising, Seasonality Significance Testing, Parameter Optimization via Multiplicative Decomposition, and Non-Parametric Error Validation.

---

### Determining the Significance of the Seasonality
* **Objective:** Verify whether recurring seasonal spikes are statistically meaningful or merely random fluctuations.
<img width="590" height="579" alt="image" src="https://github.com/user-attachments/assets/bffcac56-241f-44e2-b8dd-cc3065776709" />



### Identifying Seasonal Differences to Model Seasonality and Trends
* **Objective:** Mathematically evaluate the structural relationship between the baseline trend and seasonal variations (Additive vs. Multiplicative structural properties).



### Deseasonalizing the Model
* **Objective:** Strip away cyclical seasonal noise to isolate and track the true underlying growth or contraction trend.
<img width="590" height="576" alt="image" src="https://github.com/user-attachments/assets/f0af41a2-3342-49ab-9ff4-311915476920" />


### Applying the Least Squares Method (Model Estimation)
* **Objective:** Execute the statistical estimation engine to compute optimized parameters and assess model fitness weights.
<img width="591" height="577" alt="image" src="https://github.com/user-attachments/assets/0a155bfa-db56-4afb-9cd4-0f91ac663d32" />


###  Holt-Winters' Exponential Smoothing Model 
After completing all 5 framework steps, Holt-Winters' Exponential Smoothing (three parameters) both Additive & Multiplicative Models are chosen. Multiple evaluation metrics (SSE, MSE, RMSE, MAPE) were benchmarked across these two primary mathematical variations to guarantee high-performing, fast, and accurate insights.

### Additive Model
<img width="756" height="203" alt="image" src="https://github.com/user-attachments/assets/28acb273-23ea-4be4-b148-b89e68a11d60" />

<img width="587" height="571" alt="image" src="https://github.com/user-attachments/assets/59a5e858-da14-4a5c-9123-19a6bc9ba4ed" />


### Multiplicative Model 
<img width="797" height="167" alt="image" src="https://github.com/user-attachments/assets/1a41b88b-9194-46ed-a676-94b475746597" />

<img width="588" height="576" alt="image" src="https://github.com/user-attachments/assets/5bd5dc00-ac24-49b7-826b-347ac6176e40" />


### Forecasting 
<img width="587" height="571" alt="image" src="https://github.com/user-attachments/assets/e8b226bb-1cb5-4df7-bf0b-d9e84c59be22" />




