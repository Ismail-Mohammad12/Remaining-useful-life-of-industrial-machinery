# Remaining useful life of industrial machinery(RUL) ('Still under work')
In this project, The remaining working capability of a machine has been analysed and modeled to predict for the machine based on the sensor data such as the vibration,temperature and so on. This industrial application of AI models are extremely beneficial in terms of managing the downtime in the factories before any fault actually occurs, and provides a headstart for the personnel to perform maintenance before any fault occurs and it is also useful in saving time,money and effort where it eliminates the extremely early maintenance and provides exacty how many more cycles are there for a specific machineto go fault. The responsible personnel can set a threshold 5, where the model triggers a maintenance alarm.

The dataset can be downloaded from the folling kaggle link, where there are many different variables related to 100 machines associated with failures. 

**Result summary** : Comparison analysis revealed that catboost model has shown the best results in terms of RUL prediction ad has also passed the robustness testing where even with 20 percent of extra added noise to the actual data, The model was able to replicate 74% of the true model performance.

In the following barplot, There are multiple models acrossdifferent noise levels incorporated in the testing data for measuring for the model robustness. This test resulted in the catboost model performing the best in terms of learn the lrger extent of target distribuion where even with noise injection to the test data, the model was able to provide relaible extimation which can also be confirm use the mean absolute error scores of these models.
![R² Comparison](Plots_for_project1/Comparison_plot.png)



![My Plot](plots/ALL_MODELS_R2_SCORES.png)
