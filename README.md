# Movie-Recommendation-Engine

At first I want to tell you that I have made a ml model of Movies rating predctor. In that case I have used three datasets. 1)Movies dataset(consists of movieids, names and categories) Size-(3882,3) 2)User dataset(consists of userid, gender, age, occupation, zip-code) Size-(6039, 5) 3)Rating dataset(consists of id,movieids,ratings,timestamp when rating given) Size-(1000208, 4)

So first i have loaded all the datasets and check wheather there is null value or not and i concat those three. That final dataset Size is (1000208, 12). Then, this is a large dataset. So ia have extracted features and labels for 2000 data. Then i have applied train_test_split method and fit to variuos algorithms and checked accuracy. I have used almost all types of alorithms or types for training to get best accuracy. I have used Regression, Clustering and classification.I get the best score in Random Forest and Decision Tree Classifier. For better understanding i have made a table to display all accuracy.

I have uploaded all the datset files. But if you want then you can use url which i am providing - https://www.kaggle.com/sherinclaudia/movie-rating-prediction/data?select=users.dat

Thanks.
