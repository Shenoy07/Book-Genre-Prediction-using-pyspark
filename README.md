# Book-Genre-Prediction-using-pyspark

### Why this project?
-> We were asked to do this project as our FINAL Project for the class CIS 8795 BIG DATA INFRASTRUCTURE.

### What are you trying to do in this project?
-> We are trying to predict the Genre of the book using the summary of the book. We are using pyspark for this project.

### What models have you used?
-> We have used Logistic Regression, Decision Tree Classifier, Naive Bayes Model, and SPARK NLP.
We then tried to find the best results with cross-validation using param grid.
In SPARK NLP we tried using Universal Sentence Encoding and Bert Encoding to find the best model.

The results are mentioned in the dbc file in the conclusion section. 
Here is a snippet of the result that we got. 
The image represents the accuracy of the models and we see which model performed the best.

![image](https://user-images.githubusercontent.com/31709147/212223764-4f161854-383a-439c-8360-63c93cdbc8be.png)


### How do I run this project? 
Just open the file from your workspace. Connect it to a cluster as the steps mentioned below and run all the cells.
The book is self explanatory. If you feel there are any issues feel free to contact me.


-> Open DataBricks Community Edition, go to the panel on the left side, go to workspace and import the Book Genre Prediction.dbc file.
After the follow the given steps in the images to create a cluster and install spark nlp.

I apologize for the screenshots, but I guess they are good enough to get your work done.

![image](https://user-images.githubusercontent.com/31709147/212224147-945c484b-8a54-4d43-bb3a-4f074392bddc.png)

![image](https://user-images.githubusercontent.com/31709147/212224220-30396164-8dda-4060-a75d-e75f415961e0.png)

![image](https://user-images.githubusercontent.com/31709147/212224295-ad6a2ca1-c62a-4f31-b31e-a07f2496cbf8.png)

![image](https://user-images.githubusercontent.com/31709147/212221905-73681bf5-313b-474c-bec0-756d6d78af8b.png)

![image](https://user-images.githubusercontent.com/31709147/212224389-2f11c1dc-7a7f-48a5-bbaa-5aaefe7f05d3.png)

![image](https://user-images.githubusercontent.com/31709147/212224443-6469941f-b204-45b5-879f-fa9b67c4e824.png)

![image](https://user-images.githubusercontent.com/31709147/212224481-6468ae2b-eeb7-41b4-bfad-a81f8a33f493.png)

Select and Install
![image](https://user-images.githubusercontent.com/31709147/212222324-4f7f8b1b-a63b-4514-8a5f-893b7eedeeb6.png)

The cluster creation process and the library installation process might take a around 5-10 minutes. 


