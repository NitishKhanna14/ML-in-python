# ML-in-python
Implementing ML algorithms using Python


IMPORTANT NOTES:

1. To find the path of a file, right click on it and go to 'properties' and goto 'security', you will find the path there
2. If your dataset contains names (person name, city name, ...etc), then drop those columns *del df["column_name"]*
3. To improve the accuracy, drop the columns which get lowest value in CORRELATION MATRIX
4. If an error shows up saying that a module/package is missing, then goto anaconda prompt and enter "*conda install package_name*"
5. For train test split:
    let's consider 'a' to be no. of columns, then it's 
    "*x_train,x_test,y_train,y_test = train_test_split(df.iloc[:,0:a-1],df.iloc[:,a-1:],random_state=1)*"
6. If your dataset has got NaN values, replace it by entering
    "*df=df.fillna(df.mean())*"
7. For clustering, you don't need to do the train_test_split
8. "*df.shape*" will return you the number of rows and columns in your dataset
9. Agglomerative clustering belongs to hierarchial clustering
10. Classification algorithms --> decision tree, naive bayes, KNN (K-Nearest Neighbours)
11. Clustering algorithms --> Kmeans, agglomerative, mean shift 
