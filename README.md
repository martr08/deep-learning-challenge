# deep-learning-challenge
Module 21

Overview of the analysis

This challenge involved applicants for a charity foundation called Alphabet Soup. To assist them, I have created a neural network or deep learning model to help select applicants that would benefit them the most. Using Google Collab, I received in the CSV containing more than 34,000 organizations and coverted it to a pandas DataFrame. I dropped columns that I did not need, determining the unique values, and encoding them to categorical columns. Futhermore, I split the processed data in X and y variables and using StandardScaler() to scale the features and fit the data.

Once I have processed all of my data, I went on to create the neural network model by assigning the input features and nodes for each layer using specifically TensorFlow and Keras. Afterwards, compiling and training the model. I added 100 epochs and ran the code to see what the accuracy code was. Testing and adjusting different parameters to reach a target over 72% accuracy. I tested the data several times and was unlucky. 

Finally, exporting and saving the results to a HDF5 file to be presented to the Alphabet Soup Foundation.

Data Preprocessing
The variable and features that provided:

•	EIN and NAME—Identification columns
•	APPLICATION_TYPE—Alphabet Soup application type
•	AFFILIATION—Affiliated sector of industry
•	CLASSIFICATION—Government organization classification
•	USE_CASE—Use case for funding
•	ORGANIZATION—Organization type
•	STATUS—Active status
•	INCOME_AMT—Income classification
•	SPECIAL_CONSIDERATIONS—Special considerations for application
•	ASK_AMT—Funding amount requested
•	IS_SUCCESSFUL—Was the money used effectively

Variables that could be removed are EIN and Name which were removed in my dataset because they give no value to my data.
Variables that i targeted were classifications and value counts of the application type.

Compiling, Training, and Evaluating the Model

I used the same number of features compared to neaurons in my input data, changing from one to 2 layers and i used the sigmoid activativation. However, I was not able to reache the 75% accuracy. I did change the number of epochs and batch size to see if that would work but there may have to be data looked at as well.

Summarize
Overall my accuracy score was at 72% meaning that there is room for improvement. By processing the data to see what can be adjusted in order to help improve the accurcy score.
