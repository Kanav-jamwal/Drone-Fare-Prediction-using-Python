## Drone Delivery Price Prediction using Python 3.6.

Data Cleansing Details :
1. The data file contains 18 different columns and every column has Data Entry.
2. The major data cleansing details:
  * Date was not entered in the same format. For eg 2019/12/12 and 12/12/2019.
  * The latitude and longitude was not entered correctly as some of the data points were in the water bodies. 

  ![](Capture.png)
<br />

  * After Cleaning.
    ![](Capture2.png)
<br />
  * Distance correction between the two points using distance formula.
  * The time difference between the starting time and delivery time was one of the biggest task and has been explained in the file well.
3. Some of the data points were in wrong clusters. 

![](Capture3.png)
<br />

4. After using K-NN classifier the wrongly classified points were corrected.

![](Capture4.png)
<br />

5. Delivery time was classified into 3 time zone as Morning , Afternoon and night becaus the fare was dependent on the different time.

6. Linear Regression model was used  for the Fare calculation by taking the important factor into consideration that is R-square and Variance Inflation factor.

#### The project contains the Drone data set and cleaned dataset.