# Multivariate-Time-Series-Forecasting

# The paper is also published in IEEE and can be accessed via the following link:
[PAPER LINK](https://ieeexplore.ieee.org/document/10434951)

# Multivariate Time Series Forecasting to Forecast Weight Dynamics

# Abstract
This paper represents a multivariate time series forecasting approach to predict the weight dynamics of an insect colony. In this paper, we are predicting the Colony Weight of the Insect which has the main impact on the growth and overall health of the insects. To accomplish this task, we have performed extensive preprocessing on the time series data, ensuring data quality and suitability for analysis. Overall, we have conducted a high-level Exploratory Data Analysis which covers time series analysis to identify different patterns as well as trends present in the time series data. Following the EDA, Feature Engineering and Feature Selection techniques have also been performed to find the features that have an impact on the colony weight feature. As a follow-up, we have performed Multivariate Time Series forecasting of the colony weight for future data with Time Series Forecasting techniques such as Vector Autoregressive moving average with exogenous regressors (VARMAX) and with Deep Learning techniques such as Long Short-Term Memory (LSTM). Several statistical parameters such as AIC score, BIC score as well as MSE value along with the grid search method have been utilized to find the optimal lag value which affects the model performance significantly. The performance of the black box model has been compared with the interpretable model to find the best outcome. This paper contributes to the field of multivariate time series forecasting in the context of insect colony dynamics. Various insights that have been gained from that study have implications for understanding insect behavior, population dynamics, and overall ecosystem health. Furthermore, the proposed methodology can be extended to other domains involving multivariate time series forecasting.

# Introduction 
In general insect colony plays an important role in maintaining balance in the ecosystem as well as agriculture. Their colony weight is a significant component that affects the growth and general health of insects and this is a vital metric that gives an understating of the insect's population alongside with their impact on the surroundings. Therefore, predicting insect colony weight dynamics is a crucial task that can aid in managing and maintaining a healthy insect population. The health and expansion of insect populations, which are vital to maintaining the environmental balance, are impacted by a variety of variables. In this paper, we have tried to exploit several multivariate time series forecasting methods with an emphasis on the Colony Weight feature to anticipate the weight dynamics of insect colonies.
Univariate time series forecasting can be done using a wide variety of techniques. However, in general, the dependent variables depend on other independent features in addition to time. It is not possible to capture the relationship between the available independent variables and the desired feature using univariate analysis. Multivariate analysis is the best method for completing this task since it can capture many hidden correlations between variables as well as leverage dependencies between variables to improve forecasting accuracy [1]. In addition to extending this technique to other analytical approaches that may be utilized to perform multivariate time series forecasting.

The following diagram shows the working methodologies which have been performed to accomplish the work:

![image](https://github.com/user-attachments/assets/da173483-4bf5-4a8e-8f34-ff0fb51c9877)


