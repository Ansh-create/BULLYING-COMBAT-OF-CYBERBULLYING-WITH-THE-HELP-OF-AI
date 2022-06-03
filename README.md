# BULLYING? – COMBAT OF CYBERBULLYING WITH THE HELP OF AI

![BULLYING](https://github.com/Ansh-create/BULLYING-COMBAT-OF-CYBERBULLYING-WITH-THE-HELP-OF-AI/blob/main/crew-4Hg8LH9Hoxc-unsplash.jpg)

Through this project I proposed a cyberbullying detection model whereby several model like Naïve Bayes, SVM, DNN model is used. In addition to it , numerous methods of text classification based on Artificial Intelligence were investigated.

This experiment trial test were conducted on a global Twitter dataset which I fetched from Kaggle. The experiment of this model results indicate that through this we achieved the best accuracy and accurate score with minute loss in our dataset, also their classification accuracy and loss are 96.82% and 0.1375, respectively.

Future direction is properly based on or we can say working on cyberbully detection in various languages. Also to work on automatic detect from twitter without using the raw dataset.

## Data
Data is taken from two sources:
1.	Hate Speech Twitter Annotations
    - Publication: 
Z. Waseem and D. Hovy. Hateful symbols or hateful people? predictive features for hate speech detection on twitter. In NAACL SRW, pages 88–93, 2016 
    - Authors: Waseem, Zeerak and Hovy, Dirk
    - GitHub Link: https://github.com/zeerakw/hatespeech
    -	Description: 
The dataset contains about 17,000 Tweet ID's labeled for racism and sexism. We downloaded this dataset and querried a Twitter API to scrape the actual tweets from Twitter. Retrieval of about tweets 5,900 failed either because the tweet was deleted or the account was deactivated. 

2.	Hate Speech and Offensive Language Detection
    - Publication: 
Automated Hate Speech Detection and the Problem of Offensive Language
    - Authors: Davidson, Thomas and Warmsley, Dana and Macy, Michael and Weber, Ingmar
    - GitHub Link: https://github.com/t-davidson/hate-speech-and-offensive-language
    - Description:
The dataset has about 25,000 Tweets annotated by crowd sourcing. As per the number of users labeling the Tweets, each is put in one of three classes - hate speech, offensive language and neither. We downloaded the dataset in Python from GitHub as a csv file.<br>
The data from both sources are clubbed. Here is the distribution of the tweets into the two classes:


![Dataset](https://github.com/Ansh-create/BULLYING-COMBAT-OF-CYBERBULLYING-WITH-THE-HELP-OF-AI/blob/main/Screenshot%202022-06-03%20at%2011.01.07%20AM.png)



## Summary
![MODEL LOSS & ACCURACY](https://github.com/Ansh-create/BULLYING-COMBAT-OF-CYBERBULLYING-WITH-THE-HELP-OF-AI/blob/main/Screenshot%202022-06-03%20at%2011.01.39%20AM.png)
![MODEL LOSS & ACCURACY](https://github.com/Ansh-create/BULLYING-COMBAT-OF-CYBERBULLYING-WITH-THE-HELP-OF-AI/blob/main/Screenshot%202022-06-03%20at%2011.01.52%20AM.png)

After tuning hyper-parameters to optimize the algorithms, Stochastic Gradient Descent was found to be the best suited algorithm, taking both performance and time complexity into account.
Following performance metrics were achieve:
-	Accuracy: 96.82 %
-	Precision: 98.08 %
-	Recall: 93.75 %
-	F1-Score: 96.34 %
