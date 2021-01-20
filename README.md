# Client_Server
DONE BY Au Ling Chi ,Erick
Compile part
dev environment:python 3.8

Step 1
start with initialize and create the tcp socket,with the aid with socket library of python.
create an input variable which is the ip adress of the server.

Step 2
print out the IP adress and port number and the connect statues once connect successfully.
+Try except funciton to due with connect failure.
Step 3
due with the command function of the program.
create a while loop make user can input command many times
determine the command case users input buy if and elif
POST:
stack up the input content and send all decoded msg to server .
count the broadsize for READ function.
READ:
request msg on broad by READ command
recieve the msg and decode them 
by a for loop
revieve times = the count in POST function
QUIT 
send QUIT command to the server
Other command
directly send to the server 
recieve the msg from server

for each function 
print the relative msg in client program 

Run part

Step 1 
open both server and client program 
input ip address of the server
details of server(socket) will be shown
if connection is failed 
fail msg will be shown
Step 2 
input the command 

command 1 POST
this command allow users post msg on the broad on server
input the msg you want to post after entering the POST command
the sent msg will store on the broad in the server

command 2 READ 
this command allow users read the msg on the broad from the server
entering the READ command
the msg on the broad will be sent from server 
and be displayed on the client interface

command 3 QUIT 
this command allow users to quit the server
entering the  QUIT command
the server will disconnect with the client

WRONG COMMAND CASE
if users accidentially input others irrelevant command 
an error msg will be displayed on the client interface
