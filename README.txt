Warning:
Program is very buggy and will disconnect within 30 seconds without sending a message.



Remmerson error codes:
 
[Type of error]
###
[Program type]
C = Client
S = Server
SC = Both

C001: User attempted to send message without being connected to a server. 	(found in Server.cs)
C002: IO Exception while reading packet (message).     					(found in Server.cs)
C003: IO Exception while sending message. 								(found in Server.cs)
C004: Unexpected error while user attempted to send message.				(found in Server.cs)
C005: Client was unable to read sent message.							(found in Server.cs)
C006: User pressed "Connect" button while already connected to server.		(found in Server.cs)
S007: Client attempted to connect to the server while server is offline.		(found in Server.cs)
C008: Error occured while trying to receive file.							(found in Server.cs)
C009: Sent file received successfully.									(found in Server.cs)
C010: Sent file was sent successfully.									(found in Server.cs)
S011: Server has been shut down while Client was connected.				(found in Server.cs)
S012: Unknown client tried to connect. 									(found in Program.cs)
