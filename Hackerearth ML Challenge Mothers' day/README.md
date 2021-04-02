# Hackerearth ML Challenge Mothers' Day
### Problem Statement:
![Question_part_1](./dataset/ps1.png)
![Question_part_2](./dataset/ps2.png)

### Approach:

I started the Hackathon with a very simple approach of converting texts to numbers. Divided the complete hackathon in few simple stages:
1. Data Reading
2. Data PreProcessing
3. Text Analysis 
4. Model Building 


Data Reading:
Reading both test and train files to generate a combined dataframe.

Data PreProcessing:
Data Processing consists of following steps:
Step 1 : Converting html entities
Step 2 : Removing "@user" and "#words" from all the tweets
Step 3 : Changing all the tweets into lowercase
Step 4 : Apostrophe Lookup
Step 5 : Short Word Lookup
Step 6 : Emoticon Lookup
Step 7 : Replacing Punctuations with space
Step 8 : Removing extra white spaces
Step 9 : Replacing Special Characters with space
Step 10 :Removing all the words when http or pic comes in text
Step 11 : Replacing Numbers (integers) with space
Step 12 : Removing words whom length is 1
Step 13 : Replacing mom alternatives with "mother"
 
Text Analysis:
This gives an in depth idea of what are the most frequently occurring words in each sentiment class. This also gives an idea what the most common words are all three sentiment classes are so that we can remove them.

Model Building:
Tried 3 different models :
1. XGBOOST
2. GBM
3. AdaBoostClassifier
And finally proceeded with GBM with some hyperparameter tuning.

Link to competition page: [Link](https://www.hackerearth.com/challenges/competitive/hackerearth-machine-learning-challenge-mothers-day/problems/)

### Leaderboard: In top 2%
