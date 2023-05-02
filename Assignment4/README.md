### Description:
1. Generate a three class gaussian data using sklearn.dataset library as shown below:
```py
from sklearn.datasets import make_blobs  
X, y = make_blobs(n_samples = 500, centers = 3, cluster_std = [1.0,1.5,2.0], random_state = 0)
```   

2. Split train data in 80:20 (Train: Test) and to perform training and evaluation.   
3. Apply Gaussian Naive Bayes Algorithm with 80 percent train dataset.     
4. Not allowed to use any built-in library to make Naïve Bays model, implementation should be your own.      
5. Then test your algorithm with the 20 percent evaluation dataset.     
6. Report the accuracy of classification on the test dataset.     