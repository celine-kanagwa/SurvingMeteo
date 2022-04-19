
## Task
i have data for the path a previous meteor took during a period of 20 minutes, 10 minutes before and 10 minutes after crossing the impact region. 
i will train a model on this data and extrapolate my predictions to an 80-minute orbit to see how it compares to the scientists prediction. 
Will my orbit be similar to that of the scientists, where we don't die just by a small bit?
data set : on kaggle orbit.csv

##### Importing libraries
##### loading data 
##### Define a sequential model
##### Compile a keras model 
##### Training 
##### Evaluating
evaluate our model on this very same data, let's see if your model can learn the meteor's trajectory
##### Predicting the orbit!

I've already trained a `model` that approximates the orbit of the meteor approaching Earth and it's loaded to use.
Since i trained my model for values between -10 and 10 minutes, my model hasn't yet seen any other values for different time steps.
i will now visualize how my model behaves on unseen data.
Remember `np.arange(x,y)` produces a range of values from `x` to `y-1`. That is the `[x, y)` interval.
