# Bike Sharing Assignment

> A US bike-sharing provider `BoomBikes` has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.
>  it is  required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)


## General Information

* They want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
    * Which variables are significant in predicting the demand for shared bikes.
    * How well those variables describe the bike demands


## Conclusions

-  The linear regression model was able to predict bike demand precisely with an R2 Score of more than 80%.

- Final Equation
```
cnt = 0.2684 + 0.2355 × yr + 0.4060 × temp + 0.0696 × mnth_9 + 0.0455 × season_winter - 0.1619 × windspeed - 0.2875 × weathersit_Light Rain - 0.0771 × weathersit_Misty cloud - 0.1177 × season_spring
- 0.0965 × holiday 
```


## Technologies Used

- numpy - version 1.26.4
- pandas - version 2.2.2
- matplotlib - version 3.9.1
- seaborn - version 0.13.2
- scikit-learn - version 1.2.2
- statsmodels - version 0.14.0


## Contact

Created by [@abhishek200319] - feel free to contact me!

