# Analyse_covid19data_using_dl_algo
* This project analyzes covid19 twitter data using deep learning algorithm-LSTM
* First of all i create a LSTM model for finding sentiment score of text
* I have train and test that model using sentiment.csv file
* Then this model is used to analyse the sentiments if given tweet
* I have applied this model to every tweet in thetwitter dataset
* Finally extracting most used keywords from positive sentiment words and visualizing them.
# Procedure(Using colab):
## Creating Model:
1. Download the sentiment.csv file and upload it to google drive
2. mount the drive
3. copy the path of csv file and use it for creating dataframe
4. use the code in creating model.py file and run the code
5. the model was created
## Analyzing Data:
1. Download the 2020-04-19 Coronavirus Tweets.csv fileand upload it to google drive
2. copy the file path and use it for creating dataframe
3. use the code in analyzing_data.py file 
4. we can see the bar graph indicating sentiment scores of some positive keywords.

