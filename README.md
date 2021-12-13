# Tweets_Analysis_Python

## Testing Data are Collected from Twitter
data collecting code is modified from https://github.com/merlinymy/Twitter-API-v2-sample-code 
## Training dataset is from Kaggle:
https://www.kaggle.com/mrmorj/hate-speech-and-offensive-language-dataset

## 要做的
做 ML models 用 ‘cleanedTrain.csv’ 这个文件。
EUCleaned 和 HKCleaned 是我们自己收集的data.
做好 models 后把 EUCleaned 和 HKCleaned datasets 作为testing datasets 放到model里面

## Which file is what
Cleaning.ipynb 是把收集到的 dataset 做了完整的clean并且做了EDA

CleaningClass.py 是写的class用来clean dataset

EUCleaned.csv 和 HKCleaned.csv 是收集到的data

MLModels.ipynb 是用来build model用的file

MongoDB.ipynb 是用来收集数据用的file

忽视NewData_Cleaning.ipynb

TrainingDataSetPrep.ipynb 是clean Kaggle 上找到的training dataset 并 EDA

cleanedTrain.csv 是清理完的 Kaggle 上的Training dataset




