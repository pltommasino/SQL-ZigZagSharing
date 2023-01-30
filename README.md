# SQL-ZigZagSharing

I wanted to design and to deploy the database of a sharing company for the purpose of supporting the customer app.
The company has different vehicles and capacities (scooter, scooter, and car), distributed in major Italian cities. 
The vehicles are bookable through the app provided to the customer who can define their preferred city and view their ride history. 
In addition, the app will allow through the selection of the number of passengers to view only the appropriate means, within a radius of 1km.
Vehicles can be disabled by the administration at any time for maintenance purposes by making them not visible on the customer's app.


I wanted to design and to deploy the database of a sharing company for the purpose of supporting the customer app. 
The company has different vehicles and capacities (scooter, scooter, and car), distributed in major Italian cities. 
The vehicles are bookable through the app provided to the customer who can define their preferred city and view their ride history. 
In addition, the app will allow through the selection of the number of passengers to view only the appropriate means, within a radius of 1km. 
Vehicles can be disabled by the administration at any time for maintenance purposes by making them not visible on the customer's app.

By user we mean the real people who physically interact with the service, 
more precisely they cannot modify its structure but they can access its contents; 
they have, in addition, the possibility of being able to book up to a maximum of 6 other passengers, 
all connected to the same customer. Of each customer we want to store his first name, last name, his e-mail and his date of birth.

By passenger we mean those persons accompanied by the client, and entered by the client in the reservation itself. 
Each customer in his vehicle can accommodate a maximum of 6 people excluding the customer himself.

A means of transportation is a device used to transport people, animals or objects.

Reservation means having the vehicle reserved in advance and found available at an earlier time. 
The reservation varies according to the number of passengers that are entered. 
In the case where between 2 and 6 passengers are entered, the means available is the car; in the case where exactly 1 is entered, 
the means available are the car and scooter. If no passenger is entered in the reservation the available means assigned will be the car, scooter or scooter.

A locality is defined as a human settlement, extensive and stable, differing from a town or village in size, 
population density. The company offers service in all major Italian cities.
								
