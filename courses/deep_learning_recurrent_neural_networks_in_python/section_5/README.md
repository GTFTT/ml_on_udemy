## What I have learned
### Sequence data
 - Sequence data - data that is ordered in time or space. Uses additional parameter T for time steps, so final shape is N*T*D where D - number of features, T - number of time steps, N - number of samples.
 - For text processing we can replace all empty values with zeros.

### Forecasting
 - Prediction Horizon - how many steps ahead we are trying to predict.
 - Auto-regressive model - model that uses its own predictions as input for future predictions.