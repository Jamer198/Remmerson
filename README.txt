Last Updated 3/22/2025 5:51 PM

RULES --------------------------------------------------------------------------------------------------

Do not spread ANY personal information on this service. Do not dox anyone or look for information for harmful purposes. Do not harass ANYONE AT ALL. Make sure you respect others' privacy and please be kind on Remmerson.

If you would like to report someone, email us at TheOrbGames1@gmail.com
You can get the email again if you press the Report button in the Settings Menu

Information --------------------------------------------------------------------------------------------------

Welcome to Remmerson.
Remmerson is a project that I have started just for funsies. It is meant to bring back the look and feel of old chat services, like MSN Messenger. Right now it is pretty bare bones, but I will work on making it better.

You are not able to send files at the moment, so don't look at the error codes and go, "Woah! How can I send files???" Because you can't (yet). Those error codes are from earlier builds when I tried implementing it, but it was janky and barely worked, so I got rid of it. I'm keeping the error codes for when I try to reimplement it.

Troubleshooting --------------------------------------------------------------------------------------------------

If your sounds aren't working, make sure there is a folder in the same directory as the client named "Sounds" and make sure these sounds are named appropriately.
"Change_Theme.wav"
"Message_Notification.wav"
"User_Join_Server.wav"
"User_Leave_Server.wav"

These 4 sounds should be in the "Aqua" and "Default" folders within "Sounds".

"No.wav" should be in "Default" only.

If you cannot connect to the server and it gives you error codes, the server might be down, or you might have been banned.
If you cannot connect to the server and it doesn't give you error codes, the server is down and I will have to turn it back on.
The Join sound will play if you have actually joined or not.

If the client does not open, make sure icon.ico exists in the client's directory.

Error codes --------------------------------------------------------------------------------------------------
 
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
C008: Error occurred while trying to receive file.
C009: Sent file received successfully.
C010: Sent file was sent successfully.
S011: Server has been shut down while Client was connected.
S012: Unknown client tried to connect.
C013: Client failed to ping server.
S014: Overflow exception occurred.