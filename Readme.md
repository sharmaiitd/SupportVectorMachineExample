# Support Vector Machine
It looks at the "rebelious" cases to truly classify between variables. Example is below:
 ![Alt text](svlogic.png?raw=true "svlogic")

 In the example, the orangy-apples and apply-oranges are in the boundary. So this is a good way to mark the lines between them and more logical in cases like this.


 Important part of the code is: 
 ```
# Training the SVM model on the Training set
from sklearn.svm import SVC
classifier = SVC(kernel = 'linear', random_state = 0)
classifier.fit(X_train, y_train)
 ```

Result

 ![Alt text](svres.png?raw=true "svres")
