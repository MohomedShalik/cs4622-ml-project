# cs4622-ml-project
Pump it up :: Data Mining the Water Table challenge
GitHub link : https://github.com/MohomedShalik/cs4622-ml-project

## Data pre-processing and Feature engineering

Pandas was used to handle the dataset, all the columns in the dataset were checked by profiling functions. 
- there were columns with missing values present. 
- some of the missing values were replaced with mean values of the column and some of the columns were dropped. 
- using label encoding columns with booleans were converted to strings and categorical columns to integers.
- some of the similar columns were dropped 
- finally the data was normalized using a standard scaler

## Training 

The cleaned dataset was finally fed to a random forrest classifier which was able to achieve an accuracy of 81.83% on test dataset and 80.96% accuracy on the final leaderboard. a feature importance graph was plotted to see which feature was influenced the model most.

## Submission and Ranking



![sub2](https://user-images.githubusercontent.com/52554022/134735155-55a5003c-d164-45a1-9add-2ed22ffe222f.png)
![sub](https://user-images.githubusercontent.com/52554022/134735183-a469f457-55f4-4545-b4a0-1b4685972a1d.png)





