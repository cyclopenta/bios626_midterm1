

# Data Availability
Because the original can't be directly used by pyhthon(some format problems), I preprocessed the data and save for them for two tasks respectively. The data could be downloaded using the link before.( The access has been given to all Umich members) :   
https://drive.google.com/file/d/1Ge741NuORYoBlF__6u5Z33tzOiLcI2bZ/view?usp=share_link

# Dependecies
```
python 3.7:  
  -numpy  
  -pandas  
  -sklearn  
 ```
# Methods  
For both tasks, I have a model sweep among support vector machine, logestic regression, random forest, naive bayes and feature selection optimization using PCA. In detail, for each model we will have 5 different train-valid sets using 10-50 PCs or all the features. The model has the highest mean accuracy and lowest variance will be chosen as the final model.  
For the binary tast, the best model is logestic regression. The summary table is shown below and saved in "summary_binary.csv".  
![table_binary](https://github.com/cyclopenta/bios626_midterm1/blob/main/table_binary.png)  
