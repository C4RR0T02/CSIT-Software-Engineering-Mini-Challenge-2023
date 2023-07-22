# CSIT Software Engineering Mini Challenge 2023

## Mighty Saver Rabbit needs your help!
As a travel enthusiast, Mighty Saver Rabbit is on the lookout for the cheapest flights and hotels for an upcoming trip with his friends.

Due to his extensive research, he had a plethora of information scattered across his computer, notebook, and smartphone. He needed a way to consolidate the data and make it accessible to his friends so that they can decide on the flight and accommodation for their trip.

To solve this problem, Mighty Saver Rabbit decided to populate all the information into a database for consolidation. However, he still needs YOUR help to make the information accessible to his friends.

Follow the instructions below to complete the challenge and help Mighty Saver Rabbit!

## Creating API

### GET Request /flight
Get a list of return flights at the cheapest price, given the destination city, departure date, and arrival date.

#### Query Parameters
|--|--|--|
|Field|Type|Description|
|departureDate|String|Departure date from Singapore. <br> ISO date format (YYYY-MM-DD).|
|returnDate|String|Return date from destination city. <br> ISO date format (YYYY-MM-DD).|
|destination|String|Destination city. <br> Case-insensitive.|	



### GET Request /hotel
Get a list of hotels providing the cheapest price, given the destination city, check-in date, and check-out date.

#### Query Parameters
|Field|Type|Description|
|--|--|--|
|checkInDate|String|Date of check-in at the hotel. <br> ISO date format (YYYY-MM-DD).|
|checkOutDate|String|Date of check-out from the hotel. <br> ISO date format (YYYY-MM-DD).|
|destination|String|Destination city. <br> Case-insensitive.|


