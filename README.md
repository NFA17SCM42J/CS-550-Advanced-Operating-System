
# CS-550-Advanced-Operating-System

Entire project can be unzipped from the ConcurrentNonBlockingPriorityQueue.zip or you can have all the java files and properties file provided above.
Documents added give the way in which project can be executed along with its output and evaluation.

Concurrent Non-Blocking Priority Queue Implementation - Steps

Step 1. Unzip the project and look for the config.properties file in com/server folder to run the no of concurrent clients. 
Step 2. Enter the no of Concurrent clients to run in the config.properties file 
Step 3. Navigate to the folder "src" and run the batch file created named as "ServerRun" provided that port no is 9000. 
Step 4. Navigate to the "src" folder and run the Concurrent clients from the batch files created named as "ClientRun, ClientRun1" depending upon the no of concurrent clients entered in config.properties file. If noOfConcurrentClients are 2 then run the 2 concurrent batch files of the clients. Note: 1. These clients can also be run from the other systems provided that "IP address of the host" to be changed in the ClientChatForm.java 2. Priority of the clients can be changed from the batch files created.
Step 5. After the clients are run, enter the synchronous message from the interface opened to the clients and send. Step 6. Look if the server gives the interface to interact with higher priority client. Step 7. Enter the message that is sent to the higher priority client.
