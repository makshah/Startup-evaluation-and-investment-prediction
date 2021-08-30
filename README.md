Start-Up Evaluation and Investment Prediction


Team Members: 
Keval Chavda - 824658660
Meet Shah - 824166818


Description:
	
The goal of this project was to analyze the dataset of the start-ups and use the information to predict some new start-ups which would be successful or not. 
	
We brainstormed on a couple of questions and tried to find the answers for it by working on the dataframe in python. We intended several factors while manipulating the initial dataset such as how did the recession of 2008 hit all the start-up companies. These start-up data included data from all countries over the world in several different domains. 

Out of all the features we had to select particular features that would help us make more accurate predictions using different machine learning model. One of the features included the market areas where we found out that there are about 754 unique market areas in the entire domain. All of these markets were compared for the most successful ones. 
Moreover, we even compared the accuracies of all the machine learning model used during the project namely, Support Vector Classifiers, Decision Tree Classifier, Random Forest Classifier, K-Neighbor Classifier and Multi-Linear Regression. 
We successfully retrieved the predictions of the new data and believe that we were successful in predicting the newer values. The main aim of the prediction was to determine if a start-up would be operating and worthy of being invested in. It should basically answer the question whether if you should put your money in that company. 

We can say that we learnt how a lot of things while executing this project. Firstly we had to research and get to know about all of the financial terms such as equity, debt-financing, equity-IPO, we learnt in detail on how to analyze and search a data with no additional information. We had to try out a couple of ways to get the results we desired. It involved testing out a lot of dummy code, reaching closer to the actual output one step at a time. We even learnt on how to choose and decision making on performing feature selection as well as choosing the correct model to perform the prediction with the gathered data. 



Special Instructions to Run the Project:
	- After downloading and installing the required files, Just replace the path of the dataset to your own local dataset path.
	- Run all the cells in the provided jupyter notebook. You should be able to see the output and the details without any errors.



3rd Party Libraries:
- The only 3rd Party libraries used in our project are the 'sklearn' and 'googledrivedownloader' (gdd)
GoogleDriveDownloader
	- Installing GoogleDriveDownloader by: "pip install googledrivedownloader"
	- The GDD would directly download the dataset from my Google Drive account to your local specified folder using the link sharing option in the Google Drive. 

sklearn:
	- Installing Sklearn by: "pip install scikit-learn"
	- sklearn is a ML library for the Python, built on NumPy, SciPy and matplotlib. It features various regression, classification, clustering and several other operations pertaining to those algorithms that can be imported and called to retrieve output quickly.



List of known issues: 
We found out that the dataset lacks enough data of the start-up companies which are closed or acquired as compared to those who are currently operating. Our data even had a lot of NULL or missing values and this resulted in most of the rows being deleted as they would not help us for the accurate predictions. Hence our classification model seems a bit biased towards the predictions and believe that we could improve the predictions if we had more quantile data.



About the Dataset / Downloading the Dataset:
- The dataset is collected from the Kaggle website initially cumulated by the crunchbase team.
(https://www.kaggle.com/arindam235/startup-investments-crunchbase)
- It contains the information about start-up companies and their investments.
- Since my dataset is 12MB in size, I have included the code within the jupyter notebook to automatically download the csv file from the google drive without logging onto the kaggle account to download the dataset.






  _____ _                 _     __   __              
 |_   _| |__   __ _ _ __ | | __ \ \ / /__  _   _     
   | | | '_ \ / _` | '_ \| |/ /  \ V / _ \| | | |    
   | | | | | | (_| | | | |   <    | | (_) | |_| |  _ 
   |_| |_| |_|\__,_|_| |_|_|\_\   |_|\___/ \__,_| (_)
                                                     
