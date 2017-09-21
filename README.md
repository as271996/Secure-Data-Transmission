# Secure-Data-Transmission
The project was created in order to provide user with a single application for providing services such as sending and receiving messages 
which are encrypted and then encoded within an image using corresponding algorithms,chat with other users while ensuring the messages are 
also encrypted and tools for decoding,decrypting,reading the messages created using this application.normal applications that are used for
transmission of messages and chatting are not secured enough.They can be intercepted in the communication process by using the tools which
are  easily available on the market.This application provide solution to the above problem.The idea behind encoding of messages is that a
person cannot intercept the messages if he doesn’t know that a message exist.when we encode a message in an image the image bits are 
manipulated so that some of the redundant bits can be used for storing of the messages thereby making the redundant bits useful.other 
than this if the encoded message is somehow detected and decoded by the malacious person the encryption 
Mechanism ensures that he wont be able to decrypt the message as he won’t have the private key required for doing so also the application 
allows user to generate a new password and send it to the email of the receiver whenever a message has to be transmitted thereby making it 
impossible for anyone except the receiver to access the message.The other  feature of this application is chatting.This feature allow
multiple clients or users to communicate with each other using a single server.The messages being transmitted are also encrypted this 
encryption is done without the user knowing it.In order to send and receive messages the application uses datagram packets,inet addresses
and ports.Thus by using this application the communication process can be made much more secured and efficient. 

