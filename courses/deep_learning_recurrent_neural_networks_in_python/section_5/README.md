## What I have learned
### Sequence data
 - Sequence data - data that is ordered in time or space. Uses additional parameter T for time steps, so final shape is N*T*D where D - number of features, T - number of time steps, N - number of samples.
 - For text processing we can replace all empty values with zeros.

### Forecasting
 - Prediction Horizon - how many steps ahead we are trying to predict.
 - Auto-regressive model - model that uses its own predictions as input for future predictions.
 - Naive forecast - one of the simplest forecasting methods. It's based on the assumption that the future will be the same as the past.
In practice, it means that the forecast for a period is just the value observed in the previous period. For Time Series Data: The forecast
for the next period is equal to the value in the current period. For example, if sales were 100 units last month, the naive forecast for this month would also be 100 units.

###  LSTM and GRU
 - LSTM - Long Short Term Memory - type of RNN that is capable of learning long-term dependencies.
 - GRU - Gated Recurrent Unit - type of RNN that is similar to LSTM but has less parameters. It consists of a reset gate, an update gate and hidden state.