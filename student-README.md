# Student README

## Questions

1. The client and server have different sized buffers.  Why does it still work?

2. What happens if the buffer size on the client is changed to a value smaller than the initial `message_length`?

3. What happens if you run the client when the server is not running? 

4. What happens if you run the server while the server is already running?

5. What changes did you make to finish this assignment?

6. What resources did you use to complete this assignemnt?  Make a Markdown list of web links below.



1- that  its server don't care or know the clients bufffer

2- the  message divides into letters or size letter 

3-  when two server running happen coonection error 

4- that its already cause os error 

5- changes server.py  running while loop from accepting from the connection and added if in for the password 
   and replacing if to elif.

6- youtube links 