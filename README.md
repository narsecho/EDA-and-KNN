# EDA-and-KNN
To use google colab run this code, better to create a same path in your google drive, and upload the data file. 
The "auto" data set is from the website "www.statlearning.com"

EDA
1. Calculate mean, std and range for each feature
2. display histogram of hisF for each feature F, density  and standard deviation.
3. display scatterplots and correlations between each feature to mpg
4. compute the 5x5 correlation matrix of the 5 features;
5. Display the quantiles of "mpg" and plot as increasing quantile curve;
6. compute 5 linear regressions and compute the relative accuracies of the 5 predictors;

KNN
7. Extract 3 tables: LOWmpg, MEDmpg and HIGHmpg with quantile <33%, (33%,66%], and >66%;
8. For each feature F=F1, ..., F5, display hist.low(F) of F features for all cases in LOWmpg; and also for in HIGHmpg;
9. compute mean, std of F values for all cases with LOW mpg and with HIGHmpg; compute 90% cnofidence intervals around mean(LOW) and mean(HIGH)
10. Emplement KNN classifier:
    Randomly partition 80%/20% each one of the 3 clalsses; 
    Regroup these three partitions to construct Train and test data set; 
    use k=5;
    compute two accuracies Acc_train and Acc_test;
11. Repeat the preceding KNN for k=3,5,7,9,11,13,15,17,19,29,39; plot graph the ACC vs k and select the best k. 
