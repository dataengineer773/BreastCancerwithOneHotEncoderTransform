By defult theOneHotEncoder will output data with a sparse representation which is efficient given that most values are 0 in the encoded representation we will disable this feature by setting the sparse argument to False so that
we can review the effect of the encoding , Once defined we can call fit_transform() function and pass it to our dataset to create a quantile tramsformed version of our dataset and in th enext stepwe will evaluate 
and pridcit our accuracy
