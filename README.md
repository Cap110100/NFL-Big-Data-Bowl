Introduction:

In this notebook, we aim to predict the routes run by wide receivers during NFL plays using a sequence-to-sequence modeling approach with LSTM networks.
A key component of this analysis is transforming raw tracking data (positions, velocities, and movements of players over time) into sequences. Specifically, we separate each play into “before snap” and “after snap” frames, allowing us to treat route running as a time-series prediction task.
By training a sequence-to-sequence LSTM under this objective, we aim to capture the temporal dynamics of receiver motion and ultimately forecast the coordinates of their routes from the moment of the snap until the pass outcome.

Detailed Project Report:
https://www.kaggle.com/code/elliottscott774/predicting-wide-receiver-routes-in-the-nfl 

Note: Datasets can be found in the kaggle competetion page (https://www.kaggle.com/competitions/nfl-big-data-bowl-2025/overview) 
