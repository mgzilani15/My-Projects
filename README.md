# My-Projects
In this repository all my data science projects which is developed in Python or R will be found. Anybody can use the technique for study and research purposes only. In the list above there are some folders, which contains each project including the data, code and instruction.

Bellow you can find the summary of all the projects:

## Project of Ausgrid Energy Company:___________________________________________________________________________
In this project, A machine learning model been developed using the logistic regression. The data been taken from the company (Ausgrid energy) website, which is: http://www.ausgrid.com.au/Common/About-us/Corporate-information/Data-to-share/Solar-home-electricity-data.aspx#.Wa35zLIjHIV. The data is mainly the billing information of their customer who been using the solar panel or not, however the data was free to use for any research purposes. We been using Three tables:

          •	Solar customer information-Billing data in various time period of the day (Solar using customers)
          •	Non solar customer information-Billing information of the non solar customer data 
          •	Customer location

Our aim was to find out the Machine learning model where we can suggest the customer, whether they can save money in their bill after using the solar panel or not. 

   #### Tools: 
          •	Jupyter notebook, which came with the anaconda distribution
          •	Python 3.0+ and the following Python libraries:
                                      	1. http://scikit-learn.org/stable/ 
                                      	2. https://pandas.pydata.org/ 
                                      	3. https://matplotlib.org/ 
                                      	4. http://www.numpy.org/ 
                                      	5. https://seaborn.pydata.org/ 





## Domestic violence in NSW:_________________________________________________________________________________
This project was developed in R.  The main purposes of this project is to analyse the social data from a data scientist point of view, and highlight the findings about some facts. 

The data was used in this project was collected from the NSW census data about the domestic violence. Using these data our aim was finding the facts and trends of Domestic violence happening in NSW.  There are four data files been used to understand this situation, which are noted bellow:

          •	Data of Domestic violence (Incidents area wise)
          •	Area or  Local Government Area (LGA location of NSW)
          •	Lebel of the data
          •	Summary statistics of the data

Using these Data file we developed a RMD file which been trying to finding the situation why and how the domestic violence is trending in NSW. We developed a linear regression model with this data to explain the domestic violence in NSW. 

#### Tools: 
	R
	R Studio



## Mobile App Classifier:_____________________________________________________________________________
In this project the initiative has been taken to implement a machine learning algorithm, to classify the apps based on the description of the apps and some other data files. It has been examined four given CSV files where we tried to figure out the data pattern and tried to find out the best solution for classify the apps. From the training data.csv file where the apps description and some Colum of TF-IDF (Term Frequency- Invert Document Frequency), been tried to build the best classifier.

#### Data:
          training_data.csv: There are 20,104 rows; each row corresponds to an app. 
          training_desc.csv: There are 20,104 rows; each row is for an app 
          training_labels.csv: There are 20,104 rows; each row is for an app. 
          test_data.csv: This is a subset of the original data set 
          
#### Tools:
      •	Jupyter notebook, which came with the anaconda distribution
      •	Python 3.0+ and the following Python libraries:

                    •	http://scikit-learn.org/stable/ 
                    •	https://pandas.pydata.org/ 
                    •	https://matplotlib.org/ 
                    •	http://www.numpy.org/ 
                    •	https://seaborn.pydata.org/ 

#### Algorithm and Result:
W used the KNN algorithm for classifying app in the app market and The accuracy of the algorithm using random validation set was 55.24 %.


## Forest Cover Type Classifier :
The forest cover type data was collected from US Forest Service (USFS) where they used Geographic Information System (GIS) to determine various cartographic attributes e.g. soil type, slope and elevation. In this project there are various types supervised classification model been used to solve the problem and compare their accuracy using precision and recall. After doing some initial experiment, Decision tree, Random Forest, K-nearest neighbours (KNN) and Naïve Bayes classification algorithm been used. After analysing the results of these methods, the best model been recommended as our final model. 

#### Data: 
The data is originally located in UCI Machine learning repository, which is https://archive.ics.uci.edu/ml/datasets/Covertype. 

#### Algorithm and Result:
In order to find the best Classification Algorithm, several algorithm been used which are:
            •	Decision tree classifier            
            •	Random Forest classifier
            •	KNN Classification algorithm
            •	Naïve Bayes classifier 

#### Performance:
The overall performance measure for supervised classifier ie, precision, recall and f1-score were captured and summarised in the following table. 

              Algorithm 	   Precision	Recall	F1-score
              Decision Tree     	0.94	      0.94	      0.94
              Random Forest      	0.95        0.95	      0.95
              KNN                   0.97	      0.97        0.97
              Naïve Bayees          0.73	      0.72	      0.70

#### Overall Performance: 	
From the above table it has been observe that KNN model demonstrated the best performance which at 97% overall accuracy, however the Random Forest (95%) and the Decision Tree were also very close. 


## Titanic Data set from Kaggle:
This is my first knowledge based machine learning project.  I made the machine learning model and used various algorithm to see the performance of the algorithm and see which algorithm is the best suitable for our project. 

#### Data: 
The data is originally located in Kaggle web site.
https://www.kaggle.com/c/titanic/data

#### How to run this notebook:
          •	Upload the "titanic-ver1.ipynb" iPython 3 Notebook to Jupyter Notebook server that supports python 3.6.
          •	Download the tytanic dataset from this web site https://www.kaggle.com/c/titanic/data
          •	Upload the data file to Jupyter Server in the same folder where the iPython file was uploaded.
          •	The notebook should run fine.
          •	PS. the notebook was developed and tested in windows laptop with 16GB RAM.
          •	To installation of Jupyter Notebook, please go to https://docs.python.org/3/using/index.html
          
          
## USA housing price Data set from Kaggle:
This is a learning stage, knowledge base machine learning model, been used the linear regression model. The data been taken from the Kaggle and been used to predicting the housing price, as a supervised learning  system. 

#### Data: 
The data is originally located in Kaggle web site.
 https://www.kaggle.com/vedavyasv/usa-housing
  
















