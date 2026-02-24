# Predicting Social Media Engagement Using Machine Learning

## Objective
To evaluate whether posting time and content features can predict total engagement.

## Approach
- Converted timestamp to datetime
- Engineered hour, month, and weekend features
- Compared Linear Regression and Random Forest models
- Evaluated using R² and MAE

## Results
- Linear Regression R²: ~0.20
- Random Forest R²: ~0.13
- Time-based features explain approximately 20% of engagement variability.

## Insight
Engagement appears influenced by additional factors beyond timing, such as content quality and audience characteristics.

## Future Improvements
- Add sentiment analysis of captions
- Include follower metrics
- Perform hyperparameter tuning
- Explore boosting models
