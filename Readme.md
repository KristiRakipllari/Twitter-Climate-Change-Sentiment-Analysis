# Twitter Climate Change Sentiment Dataset

##### Human activities from pollution to overpopulation are driving up the earth's temperature and fundamentally changing the world around us. The rapid increase in greenhouse gases in the atmosphere has warmed the planet at an alarming rate, bringing about consequences for our oceans, weather, food, and health. It is one of the greatest existential threats humanity will have to face in the coming decades.

##### Thus, in this project, I tackled a sentiment analysis task that concerns the attitude of Twitter users towards man-made climate change. We look to uncover more about the perception of the climate change debate and the related beliefs through means and methods of web content mining. The features include tweets pertaining to climate change dated between April 27, 2015, and February 21, 2018, as well as the respective tweet IDs.
##### All tweets were labeled by three independent reviewers and are part of one of the following classes:
- -1: (Negative) The tweet does not believe in man-made climate change.
-  0: (Neutral) The tweet neither supports nor refutes the belief of man-made climate change.
-  1: (Positive) The tweet supports the belief of man-made climate change.
-  2: (News) The tweet links to factual news about climate change.!
![Pie Chart / Classes %](https://github.com/KristiRakipllari/Twitter-Climate-Change-Sentiment-Analysis/blob/main/Pie_Chart.png)
### Text Preprocessing
The following text preprocessing steps were used:
– Text Cleanup: Emojis and other Twitter-specific characters and symbols should be removed, especially the username.
– Tokenization: The contained text needs to be split into tokens to create the feature vector later.
– Stop word removal: To decrease the dimensionality, stop words should be removed as they do not contain any information.
– Stemming: To further reduce the size of the feature vector words should be reduced/transformed to their word stem.

### To perform sentiment analysis different methods for representing the text components TF-IDF was considered.
- Term-Frequency Inverse-Document-Frequency (TF-IDF)

### Algorithms
Since this is a classification problem, the following algorithms were to be tested and showed that have the best accuracy:
- Logistic Regression
- Random Forest

### Evaluation
The evaluation process used during this project focused on three different key aspects. That would be the evaluation measure, subsequently sampling and cross validation as well as the handling of the ”Factual News” sentiment class.
The evaluation measure utilized for optimization was accuracy.

#### Python libraries and packages to install: 
- pandas: ```pip install pandas```
- numpy: ```pip install numpy```
- scikit-learn: ```pip install scikit-learn```
- imbalanced-learn: ```pip install imbalanced-learn```
- tensorflow: ```pip install tensorflow```
- flair: ```pip install flair```
- spacy: ```pip install spacy + python -m spacy download en_core_web_sm```
- emoji: ```pip install emoji```
- nltk: ```pip install nltk + nltk.download('stopwords')```
