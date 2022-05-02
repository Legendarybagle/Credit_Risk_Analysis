# Credit_Risk_Analysis

## Overview
the purpose of this analysis was to use different machine learning algorithms on credit card data to determine which one is the best to use

## Results
* BalancedRandomForestClassifier
* * <img width="766" alt="Screen Shot 2022-05-01 at 9 21 35 PM" src="https://user-images.githubusercontent.com/39388246/166183952-932f9f1e-4ac3-4b4b-aeed-701baaef41be.png">
* * the forest classifier did extremely well with a very high precision and a high recall score
* EasyEnsembleClassifier
* * <img width="714" alt="Screen Shot 2022-05-01 at 9 30 25 PM" src="https://user-images.githubusercontent.com/39388246/166184469-8c03f3a4-b784-4cec-b6fa-1e0927883a44.png">
* * the Easy Ensamble performed even better
* RandomOverSampler
* * <img width="725" alt="Screen Shot 2022-05-01 at 9 31 57 PM" src="https://user-images.githubusercontent.com/39388246/166184566-08c81318-3d28-4d47-87d4-7968db89b71d.png">
on the random over sampler the precision was good, but the recall number being lower indicates a larger number of false negatives
* Smote
* * <img width="716" alt="Screen Shot 2022-05-01 at 9 32 57 PM" src="https://user-images.githubusercontent.com/39388246/166184636-6be6ecb7-497a-41d6-868b-8b30ccc43c00.png">
* * also indicates a larger number of false negatves
* ClusterCentroids resampler
* * <img width="722" alt="Screen Shot 2022-05-01 at 9 33 47 PM" src="https://user-images.githubusercontent.com/39388246/166184671-dd2f86cc-3b0c-4a55-a3b5-34e2c6b76a68.png">
* * this one has the lowest recall score meaning it has the largest number of false negatives
* SMOTEEN
* * <img width="727" alt="Screen Shot 2022-05-01 at 9 35 51 PM" src="https://user-images.githubusercontent.com/39388246/166184859-57389a83-90b3-4845-994b-6217146dd61f.png">
* * also indicates a larger number of false negatves


## Summary
It seems the best of these machine learning algorithms was the BalancedRandomForestClassifier. given that all the data used the same random sample, it could be that this random sample just happened to be good for it, but it also by far out-performed the others, so that is what i would recommend using, the others were still fairly good but the ClusterCentroids resampler, Smote and SMOTEEN had a large amount of false negatives and should probably be avoided.
