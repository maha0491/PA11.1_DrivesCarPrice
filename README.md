# PA11.1_DrivesCarPrice
Practical Application Assignment 11.1: What Drives the Price of a Car?
Link to Notebook: MG_PA_II_Prompt.ipynb

To whom it may concern,

I am writing to you in response to your inquiry with regards to what factors drive the price of a car. When I first viewed the data that had been provided to me, I noted that there were 426,880 used car records. The records included information regarding Region, Price, Year, Manufacturer, Model, Condition, Cylinders, Fuel, Odometer, Title_status, Transmission, VIN, Drive, Size, Type, Paint color and State. However, upon closed review of the data, I had noticed that the values for Region, VIN, Model, Odometer, Paint Color and Drive were quite varied and showed no consistency and, therefore, were left from the analysis. Upon removal of rows that didn't have values for all of the remaining columns, a dataset with 86,240 used car records were remaining.

### Using various algorithms and analyses on the remaining dataset, I was able to determine that the following 4 features showed the most impact in driving the price of a car: Title Status, Condition, Fuel Type and Transmission of the Car.
Once I was able to find there 4 key features, I then wanted to see the trend of the values within each of the 4 features. 

![TitleStatusHistPlot](https://github.com/user-attachments/assets/133bdbe6-d8dc-4768-b432-212b2468c9af)
#### Based upon the Title Status graph, I was able to determine that, with regards to specifically the Title Status, a vehicle with a Clean Title Status is highly preferred.
![ConditionHistPlot](https://github.com/user-attachments/assets/27358db1-83e0-46ec-89c4-8bbe4efa2160)
#### Based upon the Condition graph, I was able to determine that, with regards to specifically the Condition, a vehicle in Execellent Condition is highly preferred.
![FuelHistPlot](https://github.com/user-attachments/assets/0f96090a-f7dd-44cb-b1ec-4a2d6dbe7e35)
#### Based upon the Fuel Type graph, I was able to determine that, with regards to specifically the Fuel Type, a vehicle that is Gas Powered is highly preferred.
![TransmissionHistPlot](https://github.com/user-attachments/assets/42bb06b2-1e41-41d2-bb60-07c41282846c)
#### Based upon the Transmission graph, I was able to determine that, with regards to specifically the Transmission, a vehicle that is Automatic is highly preferred.

### In conclusion, in my humble opinion, I feel that Title Statuses, Vehicle Conditions, Fuel Types and Transmission types are 4 features that have a high influence in driving up the price of a car. Additionally, based on these 4 features, vehicles with Clean Titles, in Excellent Conditions, Gas Powered, and Automatic Transmissions are more highly preferred and would be of most value to Consumers.

Sincerely,
Mahalakshmi Ganesan
