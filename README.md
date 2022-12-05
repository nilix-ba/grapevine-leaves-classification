# grapevine-leaves-classification
We use the [Grapevine Leaves Image Dataset](https://www.google.com/url?sa=D&q=https://www.muratkoklu.com/datasets/Grapevine_Leaves_Image_Dataset.zip&ust=1670317500000000&usg=AOvVaw0S3HJ7H_8AqfO56n-r7npp&hl=en) to identify different types of vine leaves. 

Project Description

- Divide the data into training and test data with a ratio of 80 to 20.
- You can increase the number of images by using data augmentation. Be careful that the test data should not be from augmented data. Therefore, first, convert the data into two parts, test and training, and Augment the train part. After applying the augmentation of the training data, use 20 percent of the data as validation.
- Perform the classification operation using different CNN neural network architectures (you can use keras or pytorch library).
- Use pretrained models available on the Internet and packages.
- Use auto encoder networks for applications such as denoising or dimensionality reduction and describe the result.
- Perform 10 times of execution with random and different seeds, mention the average results.
- At the end of the report, show results of various tests in the form of a table, confusion matrix and diagram.
- Use 10 fold cross validation and report accuracy in each case. Be careful! You should not use the test data in the cross validation process.
- Compare your results with the results of the relevant articles.
