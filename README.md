

# Data Availability
To ensure compatibility with Python due to format issues, the data has been preprocessed and saved for two separate tasks. The data can be accessed via the provided link, which is available to all Umich members:   
https://drive.google.com/file/d/1Ge741NuORYoBlF__6u5Z33tzOiLcI2bZ/view?usp=share_link

# Dependecies
```
python 3.7:  
  -numpy  
  -pandas  
  -sklearn  
 ```
# Methods  
Both tasks undergo a model sweep involving support vector machine, logistic regression, random forest, naive Bayes, linear discriminant analysis, and feature selection optimization using principal component analysis (PCA). Specifically, for each model, we will have 5 different train-validation sets using 10-50 PCs or all features. The final model will be selected based on the highest mean accuracy and lowest variance. Results for the test set will be saved in **{task}_fine.txt**. The code is in the jupyter file.  
  
## Binary Task
For the binary task, the best model is logestic regression. The summary table is shown below and saved in "summary_binary.csv".  
![table_binary](https://github.com/cyclopenta/bios626_midterm1/blob/main/table_binary.png)  
  
## Multi-class Task
For multi-class task, the best model is linear discriminant analysis. he summary table is shown below and saved in "summary_multi.csv".  
![table_multi](https://github.com/cyclopenta/bios626_midterm1/blob/main/table_multi.png)

# Leaderboard Performance  
I got the 100% accuracy for task 1 and 96.1% accuracy for task 2 after my first submit and I decide to keep it.


# Ways to improve:  
We may need a better feature selection method. I suppsed to try lda for feature selection. Secondly, since we have a relatively high prediction, one suggestion is to develop a simple NN model. Lastly, I can try fine tune the model by running a hyperparameters sweep.  
