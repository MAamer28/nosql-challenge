# Module 12: noSQL Challenge
Module 12 Challenge

## Background
The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

## Data Analysis
A noSQL database titled _uk_food_ was created with a collection called _establishments_ inside it. The database was updated with the latest information and the data was cleaned/organized accordingly. The following questions were then answered via the database.

### Which establishments have a hygiene score equal to 20?
There are a total of 41 establishments in the database with a hygiene score equal to 20, including the Chase Rest Home, Brenalwood, the Melrose Hotel, Seaford Pizza, and the Golden Palace. 

### Which establishments in London have a RatingValue greater than or equal to 4?
There are a total of 33 establishments in London with a rating value greater than or equal to 4, including Charlie's, My City Cruises Erasmus, Benfleet Motor Yacht Club, Tilbury Seafarers Centre, and the Lock and Key. 

### What are the top 5 establishments with a RatingValue rating value of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
A query looking for establishments within 0.01 degrees latitude and longitude of Penang Flavors was executed. The results returned were filtered to return only those with a rating value of 5. Then, those establishments were sorted by lowest hygiene scores to return the top 5 establishments near Penang Flavors. 

Those establishments are as follows: Howe and Co. Fish and Chips, Atlantic Fish Bar, Plumstead Manor Nursery, Iceland, and Volunteer.

### How many establishments in each Local Authority area have a hygiene score of 0?
A query was constructed to determine the number of restaurants with a hygiene score of 0 in each local authority. The results were then tabulated into a DataFrame as seen in the code. 

Of the results, the top three Local Authorities with the highest number of noted establishments are as follows: Thanet (1130), Greenwich (882), and Maidstone (713). 

## References
UK Food Standards AgencyLinks to an external site. (2022). UK food hygiene rating data API. https://ratings.food.gov.uk/open-data/en-GB. Contains public sector information licensed under the Open Government Licence v3.0
