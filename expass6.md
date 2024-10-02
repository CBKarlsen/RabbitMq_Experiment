## Expass 6 - Casper Karlsen

### Experiment 1 - installation

Installing the RabbitMQ was no problem for me. I followed the instructions and used Brew to install and run the server in the background.

### Experiment 2

No problem implementing the code

[Recv](https://github.com/CBKarlsen/RabbitMq_Experiment/blob/master/src/main/java/org/example/rabbit/Recv.java)
````POM.xml 
 [*] Waiting for messages. To exit press CTRL+C
 [x] Received 'Hello World!'
````

[Send](https://github.com/CBKarlsen/RabbitMq_Experiment/blob/master/src/main/java/org/example/rabbit/Send.java)
````POM.xml 
 [x] Sent 'Hello World!'

Process finished with exit code 0
````

### Experiment 3

[NewTask](https://github.com/CBKarlsen/RabbitMq_Experiment/blob/master/src/main/java/org/example/work_queues/NewTask.java)

[Worker](https://github.com/CBKarlsen/RabbitMq_Experiment/blob/master/src/main/java/org/example/work_queues/Worker.java)

Worked as intended, had no problem implementing the code.

### Experiment 4 - topics

[EmitLog](https://github.com/CBKarlsen/RabbitMq_Experiment/blob/master/src/main/java/org/example/Topics/EmitLog.java)

[RecevieLogs](https://github.com/CBKarlsen/RabbitMq_Experiment/blob/master/src/main/java/org/example/Topics/ReceiveLogs.java)

Had no issues in implementing these, works as intended.

### Issues

I had some issue when trying to test the code. In the end I executed the code with the help of the IDE.