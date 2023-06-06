# EX-7 IMPLEMENTATION OF TRACEROUTE COMMAND

## DATE :20-04-2023

## AIM :
To write the python program for simulating Traceroute command
## ALGORITHM :

### STEP 1: Start the program.
### STEP 2: Get the frame size from the user.
### STEP 3: To create the frame based on the user request.
### STEP 4: To send frames to server from the client side.
### STEP 5: If your frames reach the server, it will send ACK signal to client otherwise it will sendNACK signal to client.
### STEP 6: Stop the program

## PROGRAM :
## Developed : MALARVIZHI G
## Reg no : 212222040096
```
from scapy.all import*
target = ["www.google.com"]
result, unans = traceroute(target,maxttl=32)
print(result,unans)
```
## OUTPUT :
![ex07 output](https://github.com/22008650/EX-7/assets/122548204/2c3b0196-22ce-4dd1-8c5f-6115847b4c8e)



## RESULT :
Thus, the python program for simulating Traceroute command was successfully executed.
