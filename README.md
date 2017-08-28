# Travel Management Project on Oracle 11g

Travel Express:
Travel Express is an application designed to help users to make their travel plans by facilitating them to book their tickets for the journey and hotels for their stay and finally generating an itinerary for their complete trip. The users have the choice to make bookings using the mode of transport of their choice. The options available for different modes of transport are - Air, Road, and Train. After selecting the mode of transport, the users have the option to select the transport service of their choice and compare the competitive rates of these services. Once the mode of transport and the travel dates are finalized, the user can then book a hotel for their stay at the destination place. Again while selecting the hotels, the user has the choice to compare the competitive rates of different hotels. After the hotel selection is done, the user can also add dependents (if any) and go to the payment page. At the payment page, the user gets the option to apply a promo code and book the trip at a discounted price. Once the promo code is applied and payment is done, the itinerary of the entire trip of the user gets generated.

Technical details of the project:
- Designed the data model of the Travel Express database using Erwin software
- Created entity models to identify the relationship between different entities
- Implemented the Travel Express database on Oracle 11g using SQL Developer
- Developed stored procedure to calculate the rates offered by different transport services between different cities. The rates were calculated on the basis of the distance between the departure and arrival cities. The distance, in turn, was calculated by using a function, which captured the latitude and longitude of the departure and arrival cities.
- Developed an interactive user interface using Java Servlets and JSP on eclipse
