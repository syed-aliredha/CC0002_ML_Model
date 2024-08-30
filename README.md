# CC0002_ML_Model
# About
 Our fake news detection system for our CC0002 project

 For our project, we want to build a Chrome extension that can determine whether a news source is fake or true, using machine learning and artificial intelligence (ML/AI). Before building the extension, we must build the model first.

First, we sourced our datasets: [ISOT Fake News Dataset](https://www.kaggle.com/datasets/emineyetm/fake-news-detection-datasets) and [WELFake](https://www.kaggle.com/datasets/saurabhshahane/fake-news-classification) from Kaggle. Then, we applied Natural Language Processing (NLP) concepts to clean and process the written data into numerical forms understood by computers. Finally, we trained and tested a few machine learning models, to see which works best in classifying news:
1. Logistic Regression
2. Naive Bayer Classifier
3. Passive Aggressive Classifier
4. Support Vector Machine
5. Neural Network Architecture

From our evaluation, we found that the neural network model works best. Therefore, we will be using this model for our Chrome extension. The detailed workthrough on how we trained our model can be found [here](https://github.com/syed-aliredha/CC0002_ML_Model/blob/main/CC0002_ML_Model_Better.ipynb).

 *To run the entire code, please download additionally the WELFake Dataset from kaggle. The link is in the Jupyter notebook.

