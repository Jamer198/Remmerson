Welcome to Remmerson.
Remmerson is a project that I have started just for funsies. It is meant to bring back the look and feel of old chat services, like MSN Messenger. Right now it is pretty bare bones, but I will work on making it better. 
You are not able to send files at the moment, so dont look at the error codes and go, "Woah! How can I send files???" Because you can't. Those error codes are from earlier builds when I tried implementing it, but it was janky and barely worked, so I got rid of it.

Sound troubleshooting:
If your sounds aren't working, make sure there is a folder in the same directory as the program named "Sounds" and make sure the sounds are named appropriately.
"Change_Theme"
"Message_Notification"
"User_Join_Server"
"User_Leave_Server"


Error codes:
 
[Type of error]
###
[Program type]
C = Client
S = Server
SC = Both

C001: User attempted to send message without being connected to a server.
C002: IO Exception while reading packet (message).
C003: IO Exception while sending message.
C004: Unexpected error while user attempted to send message.
C005: Client was unable to read sent message.
C006: User pressed "Connect" button while already connected to server.
S007: Client attempted to connect to the server while server is offline.
C008: Error occured while trying to receive file.
C009: Sent file received successfully.
C010: Sent file was sent successfully.
S011: Server has been shut down while Client was connected.
S012: Unknown client tried to connect.
C013: Client failed to ping server.
