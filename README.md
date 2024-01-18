# Analyzing Customer Churn for a Cellular Provider Using KNN
Churn data from a cellphone company can predict customer churn by assesing multiple features. In the .csv file there are 15 features the user can choose from when we apply the K Nearest Neighbor Algorithm. The goal of this assignment is apply KNN to new data and see how well the model is able to classify the churn data as TRUE or FALSE.
KNN can make highly accurate predictions as a supervised machine learning classifier Before applying KNN to the dataset, I ran several iterations of the model using different features.
**Installation**
This code was written and set up for classification within Google Colab.
1) Access Google Colab and open a new notebook
2) Clone the repository in Google Colab using
!git clone https://github.com/your-username/your-repo.git
3) Or access repository by using Github tab in Colab interface and copying/pasting the Github URL in the search field
4) Upload churn.csv from repository into Google Colab
5) Run code and explore
**Data Sources**
Open source data provided from UMGC faculty.
**Code**
The code relies on the following libraries
-Numpy
-Pandas
-Matplotlib
-Seaborn
1) Import the necessary libraries
2) Exploratory data analysis: modeling the features with andrew curves plot, heat correlation maps, box plots, checking for null values, and data typing
3) Train/Test split of data
4) Fit the classifier to the training set, adjust the number of neighbors later to fit the optimal number of neighbors
5) Use a confusion matrix and classification to assess results
6) Paramter tune number of neighbors in KNN using cross-fold validation
**Results**
I discovered that the optimal number of neighbors is 9. KNN is a classification algorithm that uses data points and their location to classify a new one. Optimal neighbors can control if the classifier is underfitted or overfitted to data. The classifier I coded was 90% accurate with a 99% recall and 90% precision.

**Future Work**
KNN can be simple classifier to use on data in a supervised settings. Preventing customer from leaving your company, specifically this cellular company, can be identified in the features through learning what features had the most impact on making the churn value TRUE.
