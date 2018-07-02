
# Forest Cover Type Classifier :
The forest cover type data was collected from US Forest Service (USFS) where they used Geographic Information System (GIS) to determine various cartographic attributes e.g. soil type, slope and elevation. In this project there are various types supervised classification model been used to solve the problem and compare their accuracy using precision and recall. After doing some initial experiment, Decision tree, Random Forest, K-nearest neighbours (KNN) and Naïve Bayes classification algorithm been used. After analysing the results of these methods, the best model been recommended as our final model. 

### Data: 
The data is originally located in UCI Machine learning repository, which is https://archive.ics.uci.edu/ml/datasets/Covertype. 

### How to run this notebook
      •	Upload the "Forest-coverType-Classifier.ipynb" iPython 3 Notebook to Jupyter Notebook server that supports python 3.6.
      •	Download covtype.data.gz from 'https://archive.ics.uci.edu/ml/machine-learning-databases/covtype/covtype.data.gz' and unzip             the archive file. This will produce 'covtype.data' file.
      •	Upload the data file to Jupyter Server in the same folder where the iPython file was uploaded.
      •	The notebook should run fine.
      •	PS. the notebook was developed and tested in windows laptop with 16GB RAM.
      •	To installation of Jupyter Notebook, please go to https://docs.python.org/3/using/index.html


### Tools:
      •	Jupyter notebook, which came with the anaconda distribution
      •	Python 3.0+ and the following Python libraries:

                •	http://scikit-learn.org/stable/ 
                •	https://pandas.pydata.org/ 
                •	https://matplotlib.org/ 
                •	http://www.numpy.org/ 
                •	https://seaborn.pydata.org/ 

### Algorithm and Result:
In order to find the best Classification Algorithm, several algorithm been used which are:
            •	Decision tree classifier            
            •	Random Forest classifier
            •	KNN Classification algorithm
            •	Naïve Bayes classifier 

### Performance:
The overall performance measure for supervised classifier ie, precision, recall and f1-score were captured and summarised in the following table. 

              Algorithm 	   Precision	Recall	F1-score
              Decision Tree     	0.94	      0.94	      0.94
              Random Forest      	0.95        0.95	      0.95
              KNN                   0.97	      0.97        0.97
              Naïve Bayees          0.73	      0.72	      0.70

### Overall Performance: 	
From the above table it has been observe that KNN model demonstrated the best performance which at 97% overall accuracy, however the Random Forest (95%) and the Decision Tree were also very close. 




