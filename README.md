# pakistani-olx-car-data-set-predication-by-random-forest
This project is about olx car data set predication
# step -1:Data collection
Data is collected from kaggle website.
# Step 2 Data preprocessing
First of all data is converted to data frame. Then view null values and apply two technique on missing values. one is replacing with mean and other with top values. After this converted year column to age by 2021-df["year"].Then converted categorical variable to numerical by using dummy variable. 
# X y variable
After this divide the variable into x and y variable.
# Scaling
After this applied scaling to data set by using min max scaler.
# train test split
After this split data into train test data with 20% test data
# Model applying
After this applied random forest algorithm for predication.
# pickle
After this save our model by using pickle.
