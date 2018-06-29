# Ausgrid-data
A complete machine learning project Finding some facts like the hypothesis testing and build and implement the machine learning model from solar electricity data of Ausgrid Company .

# Problem
Depending on the usages of the electricity amount, it is possible to give the right answer to the people, what sized panel they can use or buy. Since when the solar panel came to the market, the debate is going on whether should we use the solar panel or not? In a certain period of time the installation cost will be overcome by the billing amount or not?

Some people also argue that how many years it is possible to use the solar panel after the installation of the panel first time in the house. Some people also want to see the installation cost according to the size of the panel and some want to see the curve of solar and non solar billing situation.

In this process our findings is to analysis the data got from the Ausgrid company and try to find out the proper answer of the above questions raised.




# Files
# Data
The solar home electricity data is available in the link: 
http://www.ausgrid.com.au/Common/About-us/Corporate-information/Data-to-share/Solar-home-electricity-data.aspx#.Wa35zLIjHIV. 

The company published their data and keep it available for the government, researchers or the individuals whoever want to use the data for research purposes. From the various data set the monthly data is been downloaded which is in the zip format of the size 13 MB. Once after decompress the file it become 66 Mb in three csv files. All three files are non solar monthly data file of 4064 customers, solar monthly data of 2657 customers and the notes file of the solar and non solar customers. From that notefile further two csv file I make and named as solar site and non solar site of attributes in my data folder. This two file data is already given in the notes file.

Once the data is been gathered we used python pandas data frame with the Jupyter notebook. The data also been seen by using the notepad and excel. Since the file size is bigger we observed the explanation of the data after using the pandas. However the PostgreSQL been also used with the Jupyter Notebook for the further explanation and exploring of the dataset.

Observed Using pandas the solar monthly data of the customer. where there are 2657 customer, having there monthly data starting from January 2007 till Dec 2014.total more than 1378654 row of data been taken. the customer was chosen from the random amount of customer ,is using the Ausgrid solar panel. this data file is given as a csv file format. It is also observed that, in the original csv file some data shown as 1.201, 2.201,3.201 etc is actually read as 1.2010,2.2010,3.2010 which is correct in reading in pandas Data frame. so date format is good for our future data analysis.

On the other hand, Non solar monthly data was taken from the non solar 30000 customer of Ausgrid. the data is obtained as csv file format and it is from 2007 till 2015. total number of row of data obtained from the non solar site is 1163018.

Data was almost clean and there was no further cleaning required, however using pandas library function we observe that there was no Null values found in any of the field of the dataset. Using the jupyter notebook it has been also observed that the structure of the data is also clean and nice in format. In order to visualise the data Tableau software is been used, which seems was very useful tools for comparing the different trend of data.

# Data Exploring:
While the three of the data files was explored, it has been noted that the solar monthly data has 2657 customers data, having there monthly data starting from January 2007 till December 2014 total more than 1378654 row of data been taken. the customer was chosen from the random amount of customer is using the Ausgrid solar panel. this data file is given as a csv file format. On the other hand, in the non solar monthly file Non solar monthly data was taken from the non solar 30000 customer of Ausgrid. the data is obtained as csv file format and it is from 2007 till 2015. total number of row of data obtained from the non solar site is 1163018. There was a note file in csv format where two more excel sheet contains the data of the sola and non solar attribute of the customer. For further explore purposes from this two files, two more csv file been produced.

While it was so difficult to explore the data from excel file, the data been explored from jupyter notebook and the tools been used is python and pandas data frame. From the data frame of panda, while some function been used, we can see the data is almost clean and there was no null value contains in the tables. For further analysis, all the csv files been transferred in to the database of PostgreSQL and explore from there. In order to minimise the technical difficulties, using the jupyter notebook and python commend SQL tables also been explored. Since the PostgreSQL is open source and it can be predict that in the stage two of this project we have to make so many quires and that result will be easily possible to transfer in various data visualization tools without using too much coding.

# Finding the attributes:
Once we have the table and we have seen that the solar table having the attributes of customer id,
Netwk Bill Rate Type (various type of bill has been calculated in various part of day), consumption month in a format of mm/yyyy, sum(sum of consumption) and unit of me(kwt or day), on the other hand same sort of field has given in the non solar customer. However the note file was having the description of the data and two more tab where we found the attributes of solar and non solar customer. We observed that solar customer have field of Customer ID, Generator Capacity, LGA, (location/suburb), Postcode. Almost same sort of attributes been observed in the non solar customer, while they don’t have the generator capacity field.


# Installation
Copy the Jupyter notebook Ausgrid-model.ipynb as well as the data files data.csv to your python environment and open the notebook. You can begin exceuting the cells from the top. Everything should work seemlessly as long as you have the typical pandas, numpy, etc. installed.

This project requires Python 3.0+ and the following Python libraries:

NumPy Pandas matplotlib scikit-learn

You will also need to have software installed to run and execute an iPython Notebook

We recommend you install Anaconda, a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.


# Code
Python code for the project is in Ausgrid-model.ipynb.

