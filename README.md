# Curse_Of_Dimensionality

The first plot is between a distribution containing two features.

![cod1](https://user-images.githubusercontent.com/55191934/76142748-6e4b2200-6096-11ea-981d-cb93896dded9.PNG)

The second plot is also between two features.

![cod2](https://user-images.githubusercontent.com/55191934/76142754-81f68880-6096-11ea-8318-f9a7dce58b38.PNG)

Now combining these two distributions, i.e: the features have been added.

A logistic regressor is trained to classify between the dataset.
The slant line depicts the classification between the latter pair and the vertical dotted line does between the former pair.

![cod3](https://user-images.githubusercontent.com/55191934/76682749-97cef500-6624-11ea-9caf-52b11764da05.PNG)


As more and more features get added, the data is densely populated, it is unable to classify distinctly any clusters or trends.
The level of confusion increases with dimensionality.

This is known as the curse of dimensionality.
