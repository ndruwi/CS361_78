# CS361_78
This is a guide on using the microservice implemented for partners Dessert App. It covers how to receive and request. This microservice uses spike.txt as the communication pipe between program and microservice

#Sending a request
To send a request, the user must print into the spike.txt file either an integer or an order. The microservice will then process the data in the file and either add the new order or return all the orders sent to the microservice.

#Receiving a response
The program can recevie a response from the microservice by also looking into the .txt file as that is where the output of the function will go if requested. 

#Warnings
1. When making a request that requires a response, make sure to request first as data may be from a different call if reading the spike.txt file beforehand
2. Run program in the background
