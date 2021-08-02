# AdDetector
## **What is this?**
AdDetector is a machine learning algorithm that, by using a dataset of the properties of ads and non advertisement images on a webpage, can detect if a image is an ad or not with high accuracy. The program uses a Decision Tree Learning Algorithm to account for the many different variables and to reduce overfitting. However the dataset used to test it is a little dated and the algorithm would need to be changed to adapt to more modern ads.

The algorithm uses a random part of the dataset to learn from and then trys to predict the remaining part of the dataset based on what it just learned.



## **Goals of the project**
- To develop a program using machine learning to properly identify whether an image taken from a website is an advertisement or not.
- Hypothetically, this would allow an internet browser extension to use this program to identify advertisements and block/remove them
- The hope of this project would be to lay groundwork for future projects as web advertisements change.

## **Data set:**

The data set I am using is an "Internet Advertisements Data Set" from UCI Machine Learning Repository. The Data Set has 3279 Instances and 1558 Attributes. The features encode the geometry of the image (if available) as well as phrases occurring in the URL, the image's URL and alt text, the anchor text, and words occurring near the anchor text. The data is either an integer or a binary value. The dataset also lists whether it is an ad or not.


# Built With:
- python
- matplot

# Pictures:
### **Here are some the resulting data plots of the accuracy .**
![AD1](https://user-images.githubusercontent.com/87416441/127925749-74a110e8-671c-4e21-8bcb-95b282c1edb2.png)
![AD2](https://user-images.githubusercontent.com/87416441/127925763-3ac03caf-998f-429d-990d-1a9beb81e339.png)
![AD3](https://user-images.githubusercontent.com/87416441/127925768-c9782a39-7a9b-47eb-aad7-395c759894d2.png)

It is good that the accuracy is only close to 100% because 100% accuracy means that the algorithm is not making predictions and is only repeating its saved data.
