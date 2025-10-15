# Multi-tab-Health-Calculator
# BME Health Calculator Suite
Build multi-tab health calculator app using Gradio
_________________________________________________________________________

First Tab : BMI Calculator
	Users are required to input their height and weight. A BMI (body mass index) calculator determines your body size by dividing your weight in kilograms by height in meters squared. Users can choose to insert their weight in either kg/lbs, additionally for height in cm/inches. 


Second tab : Metabolic Rate 
              Users are required to input their age, height, weight and their activity label. This tab allows users to find out Basal and Total Daily Energy expenditure (BMR/TDEE). The BMR is calculated using the Mifflin-St Jeor equation as it’s widely considered to be more accurate in the modern era. 

              
men = (10 x weight in kg) + (6.25 x height in cm) - (5 x age in years) + 5


women = (10 x weight in kg) + (6.25 x height in cm) -(5 x age)  - 161


TDEE = BMR x Activity Factor  


Calories to Lose weight = TDEE - 500

Calories to Maintain = TDEE 

Calories to Gain weight = TDEE + 500

Level of Activity :

Activity factor 

Sedentary - 1.2

Light active - 1.375

Moderately active - 1.55

Very active - 1.725

Extra active - 1.9


Third tab : Food tracker
	Users are required to input the type of  food they consumed or manually input the total number of calories during that day. The tab will provide users with information regarding their calories on selected date and its comparison to TDEE. The information for the calories of each food type is achieved from the common food dictionary, and the number of TDEE for a person can be used from the previous tab.

Fourth tab : Data trends
Users can download the data of their BMI, Metabolic rate, and their daily food intake along with their calories from the first three tabs to visualize trends of their historical health data.
