## Allergy_friendly_hotels
Web scraping from Booking.com, data cleaning, analysis, visualisation with Tableau

# Project Description
As an allergic to pets, planning any trip, I always face a problem - to find a hotel that does not allow accommodation with pets. Booking.com has plenty of different filters such as "Adults only", "Pets allowed" and many others, but not "Pets are not allowed". In this project I am analysing data from booking.com in order to define Hotels that do not allowed pets. I check which European city has more “no pets hotels” and compare price and hotel score of “Pets" and “No pets" hotels.

# Hypotheses / Questions
My Null hypotesis are: Prices and hotel's scores of "No pets" and "Pets" hotels are iqual. Alternative hypotesis: A price of "Pets" hotels is higer, as special deep cleaning is required.

# Dataset
With web scraping I collected information about European hotels : names, links, score on booking.com , price for room rate and info “Pets allowed” or “Pets not allowed”. I chosed 5 europeans touristic city with more than 500 hotels available on booking.com for the 30.03 : Barcelona, Amsterdam, Lisbon, Paris, Rome. From each of these cities I received information about 500 hotels (first 500 hotels according booking.com search, sorted by booking.com “top picks”).

# Cleaning
After cleaning proces I had data that contained 2367 properties information. Rome 496, Paris 495, Lisabon 472, Barcelona 467, Amsterdam 437. In a cleaning proces I droped all the hotels with missed information and also with unrealistic values such as room rete egual to 1 eur. Prices and links were cleaned with regex.

# Analysis
All the information I recived about pets accommondation I divided into two groups ("Pets are allowed", "Pets are not allowed"). Also I divided prices into 3 price groups ("Cheap", "Normal", "Expensive"). With seaborn ploting I investigated price and score tendancy grouping by city and pets features. In statistical analisis I used stats.ttest_ind function.

# Conclusion
My Null hypotesis could be rejected. Price and score differ statisticly significant. The most expensive city is Paris and the cheapest is Lisabon. Most pets friendly is Paris, and not pets friendly is Lisabon. Amsterdam has no "Cheap and Pets are allowed" hotels. Barcelona, Amsterdam and Lisabon have more hotels in group "Normal price and Pets not allowed". Paris - "Expensive and pets allowed". Rome - "Normal and Pets allowed". "Pets allowed hotels" are more expensive. There are more higly rated "No pets" hotels than "Pets" hotels.

# Links
Vizualisation with Tableau https://public.tableau.com/profile/daria4279#!/vizhome/Finalproject_16080338645630
Presentation file:///Users/daragavrilova/Downloads/slides-deck-9b2441.html
