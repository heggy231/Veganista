# Veganista

Veganista is a vegan nutrition tracker that allows users to be aware of whether they are satisfying their daily nutritional requirements. 

### Tech

* Flask 
* PostgreSQL 
* ChartJS 
* Edamam API 
* AutocompleteJS  
* JQUERY 
* Javascript/HTML/CSS

Veganista is open source on Github.

### Features

* Enter in dishes: Users can enter in dishes which they have eaten. A new dish entry not already stored within the database will make a post request to the Edamam API which will return a JSON string including the daily percentages of carbohydrates, protein and fat the user satisfies through eating the meal. 

* Dish Nutrition: Users can click on a dish and view the daily percentages of fat, carbohydrates and protein they have satisfied through eating that dish through a polar area chart.

<img src="/search.gif" alt="search">

* Dish Directory: Users can view the list of dishes they have entered into Veganista. 

<!-- <img src="/dish_directory.png" alt="dish_directory"> -->

* Dishes by Day: Users can view dishes they have eaten on a particular day. 

<!-- <img src="/time_dishes.gif" alt="time"> -->

* Daily nutritional progress: Users can view a bar chart that shows them the total percentages of fat, protein and carbohydrates they have consumed for the day, giving them an estimate of how much more they need to consume, or whether they have exceeded their recommendations. 

<!-- <img src="/daily_progress.gif" alt="time"> -->

* Overall nutritional progress: Users can view a line chart that shows them their totals of fat, carbohydrates and protein percentages over time, so that they can gauge whether they are improving their nutritional intake or not. 


### Version 2.0
* Send users daily reminders through text to intake daily supplements of Vitamin B-12 and Nutritional Yeast through the Twilio API 
