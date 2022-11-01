# CS-361

A. To request data from the microservice, write an integer into into a txt file called hit-service.txt while having the microservice running in the background.

Example Call while microservice is running:

  with open('hit-service.txt', 'w') as f:
    f.write(25)
    
B. To recieve data from the microservice, have a txt file called calc-service.txt that the microservice will send data through. Once it receive a request, it will write the appropriate data into calc-service.txt. 
