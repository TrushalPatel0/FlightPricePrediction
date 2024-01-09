
# **Flight Price Prediction**
-----------
## **Business Case-Study**

Flight ticket prices can be something hard to guess, today we might see a price, check out the price of the same flight tomorrow, it will be a different story. We might have often heard travelers saying that flight ticket prices are so unpredictable. That’s why we will try to use machine learning algorithms including: Linear Regression, Decision Tree, Random Forest, Gradient Boosting and XG-Boosting to solve this problem. This can help airlines by predicting what prices they can maintain.

------
## **Dataset Description**

This Dataset consists Total of 10 Features and 1 Target(Price).

1) Airline: All types of airlines like Indigo, Jet Airways, Air India, and many more.

2) Date_of_Journey: Date on which the passenger journey will start.

3) Source: Name of the place from where the passenger journey will start.

4) Destination: Name of the place to where passenger wanted to travel.

5) Route: Route through which passengers have opted to travel from the source
to their destination.

6) Dep_Time: When the passenger will depart from source.

7) Arrival_Time: When the passenger will arrive to destination.

8) Duration: Whole period that a flight will take to complete its
journey from source to destination.

9) Total_Stops: In how many places flights will stop.

10) Additional_Info: Information about food and other amenities.

11) Price: Price of the flight for a complete journey including all the expenses
before onboarding.

-------
## Features with respect to Price
![image](https://github.com/TrushalPatel0/FlightPricePrediction/assets/144200919/91e516ed-0379-40b6-b486-eebfd8b79d96)

![image](https://github.com/TrushalPatel0/FlightPricePrediction/assets/144200919/e793cd9a-c952-49e0-966c-33e2e0021d4f)

![image](https://github.com/TrushalPatel0/FlightPricePrediction/assets/144200919/6a6784d0-1a16-416f-a4a8-884609e56cfd)



--------
## **Model Creation**

1) Linear Regression

2) Decision Tree

3) Random Forest

4) Gradient Boosting

5) XG-Boosting


---------
### Model Comparison Report

<img width="461" alt="image" src="https://github.com/TrushalPatel0/FlightPricePrediction/assets/144200919/515ab0d3-e91a-4625-b63a-f87a12114283">

---------

![image](https://github.com/TrushalPatel0/FlightPricePrediction/assets/144200919/5c6b10db-56d3-4f8a-b4db-82659b6fb577)


--------
## **Challenges faced**:

We have to work in EDA part for features like Date_of_Journey, Duration, Dep_Time, Arrival_Time.

From Date_of_Journey we generate two columns Day and Month.

From Duration we converted it into minutes as Duration_Mins.

From Dep_Time and Arrival_time we have to convert time-zones into Morning,
Afternoon, Evening and Night slots accordingly.

Logic of these conversions is little bit tricky.


-------------
For More Information
Please review the full analysis in the [final notebook](https://github.com/TrushalPatel0/Earthquake/blob/master/EquakeDamagePred.ipynb).

For any additional questions, feel free to email me at [business.trushalpatel@gmail.com](mailto:business.trushalpatel@gmail.com)
