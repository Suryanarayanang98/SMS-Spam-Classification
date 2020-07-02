# SMS-Spam-Classification

This is a simple SMS spam classification model. Here this dataset is obtained from kaggle.

Data Source Link: https://www.kaggle.com/uciml/sms-spam-collection-dataset

The SMS Spam Collection is a set of SMS tagged messages that have been collected for SMS Spam research. It contains one set of SMS messages in English of 5,574 messages, tagged acording being ham (legitimate) or spam. 

Here in this dataset, I am going to perform a simple Bag of words technique for spam classification. Please Note this model may not be a very robust model, since this technique depends on the text on the data,so this might not give accurate results on recent real life spam/ham messages.
## Data Preview
![Screenshot from 2020-07-02 12-58-33](https://user-images.githubusercontent.com/64247956/86329577-fa93dd00-bc63-11ea-9ea2-f4de9eadde8f.png)


## Model
I Have used Linear models like <b>Logistic Regression</b> in this project as it was giving better f1 scores. 
Since the input data is very sparse, it was expected that linear models will perform better in such cases.

## Performance of Logistic Regression

                precision    recall   f1-score  support

         ham       0.93      0.97      0.95       225
        spam       0.97      0.93      0.95       224
    accuracy         -         -       0.95       449
    macro avg      0.95      0.95      0.95       449
    weighted avg   0.95      0.95      0.95       449
