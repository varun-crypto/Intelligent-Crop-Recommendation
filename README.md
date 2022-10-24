# Crop Recommendation For Indian Agriculture
The Crop Recommendation System aims to provide information to the farmers on the soil and crop characteristics.With this information the farmer can understand which crop can be cultivated based on the soil features.This will further give insights on how to grow the crops throughtout the year to increase their profit.

Proces: A machine learning model is developed to compare the inputted soil with the authorized government soil database.When a certain type of soil matches with the soil database,the list of crops that the particular soil matches is displayed as output by comparing with the crop database.Similarly,the siutable soil for the particular crop is found by comparing it with soil database and pointing out the discrepancies in the soil if any.

Features:

1) Recommends crop feature:
For the inputted soil values,the model recommends a list of crops suitable to grow.

![image](https://user-images.githubusercontent.com/69026838/197508413-e49377ff-ea93-4a2b-a5dd-6f3520a1e933.png)


2) Recommends soil condition feature:

For the inputted soil values along with the crop name,the model recommends the soil conditions suitable for the crop.

![image](https://user-images.githubusercontent.com/69026838/197508587-b9cd8313-b870-4a30-8822-cdeda2b1cfae.png)


3) Prediction of Crop Price:
For inputted location along with date, temperature, humidity, Ph value and rainfall crop name and price is pridicted.

![image](https://user-images.githubusercontent.com/69026838/197509362-a26f4789-bd37-48b3-b82a-f02ea66e0414.png)


Benefits:
*Provides a list of crops for a particular soil condition.

*Acts as a knowledge source for the farmers to understand which crop will or will not grow for particular soil condition.

*If the crop chosen by the farmer will not grow for the inputted soil values,then the software suggests alternatives to implement on the soil.

Accuracies:
Random Forest - 94%
Support Vector - 82%
Decision Tree - 86%

So according to the above accuracies Random Forest was decided to be the best alorithm for this predition.
