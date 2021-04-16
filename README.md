# Predict_Popular_Reddit_Meme
This is my capstone design project to use Machine Learning and a Neural Network that uses image classification to predict between popular and unpopular Reddit Memes from 2014-2018.
README.txt

David Arnold 
orion99da@gmail.com
Data Science Winter 2021 Cohort

Using Machine Learning to Determine What Makes a Reddit Meme Popular

This project uses a collection of memes from Reddit during 2014-2018 that will use machine learning algorithms and image classification to predict what is a popular vs un-popular meme on Reddit.
Here is the link the dataset used in this project:  https://www.kaggle.com/sayangoswami/reddit-memes-dataset?select=memes
 

Project Contents: 

Project Report and Presentation(folder):
1. David Arnold Machine Learning to Predict a Popular Reddit Meme formal report.pdf - (This is final report for the entire project)
2. David Arnold Machine Learning to Predict a Popular Reddit Meme demo presentation.pdf - (This is the presentation prepared for Demo Day)
3. David Arnold Machine Learning to Predict a Popular Reddit Meme final presentation.pdf - (This is the final presentation presented to the Data Science cohort)


Python workbook files:
1. David Arnold Reddit Meme Viral Prediction workbook 1.ipynb - (Importing Data, Data Cleaning / EDA)
2. David Arnold Reddit Meme Viral Prediction workbook 2.ipynb - (Coverting Features to Numerical Values)
3. David Arnold Reddit Meme Viral Prediction workbook 3.ipynb - (Machine Learning Models)
4. David Arnold Reddit Meme Viral Prediction workbook 4.ipynb - (Neural Network / Image Classification)


csv (folder):
1. df_json.csv - csv datafile - (This is the dataframe when the json data was converted to tabular data)
2. df_json_2.csv - csv datafile - (Dataframe after dropping the down_votes column, feature engineering date columns from date posted column)
3. df_json_3.csv - csv datafile - (Dataframe binning the users/authors into single post user vs multiple post users)
4. df_json_4.csv - csv datafile - (Dataframe feature engineering thumbnail pixel area from thumbnail width and thumbnail height)
5. df_json_5.csv - csv datafile - (Dataframe removing non-numeric columns: date posted, author, id number, media link)
6. df_json_6.csv - csv datafile - (Dataframe removing the up votes column since there is a binomial popular memes column)
7. X_test_1.csv - csv datafile - (Dataframe of the X_test_1 data, for the train-validation-test data split)
8. X_train_1.csv - csv datafile - (Dataframe of the X_train_1 data, for the train-validation-test data split)
9. X_validation_1.csv  - csv datafile - (Dataframe of the X_validation_1 data, for the train-validation-test data split)
10. y_test.csv - csv datafile - (Dataframe of the y_test data, for the train-validation-test data split)
11. y_train.csv - csv datafile - (Dataframe for y_train data, for the train-validation-test data split)
12. y_validation.csv  - csv datafile - (Dataframe for the y_validation data, for the train-validation-test data split)

json (folder):
1.  db.json - Database file of json data from the Reddit data. - (This is the json database file that was downloaded from Kaggle, this has all the semi-structed data such as title, date posted, user name, upvotes, downvotes, image link, thumbnail image link, thumbnail image size)


memes (zip file):
memes.zip - This is a zip file of the "Good Memes" and "Bad Memes" in addition to a folder with several other memes that will be run in workbook #4, the image classifcation notebook.
            The link to download this zip file is here: https://drive.google.com/drive/folders/1KPzmIiNDYxj0IaJ9Kk6byoh7eJHlYUxq
            Unzip this file in the same folder that you are using for the Python workbooks.  It will create a memes folder necessary for workbook #4 and contain all the "Good" and Bad" memes.
