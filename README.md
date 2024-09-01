Project Description: Encryption and Decryption using AES Algorithm
Objective: This project aims to implement secure communication between a server and client by leveraging the Advanced Encryption Standard (AES) algorithm. The system focuses on encrypting and decrypting messages exchanged between the two entities, ensuring data confidentiality and integrity.

Functionality:

Message Storage and Management:

The server and client communicate by sending messages to each other.
Every new message sent is securely encrypted using the AES algorithm before being stored in a local file system on the server.
The system maintains a record of all messages exchanged, ensuring that each message is stored in an organized manner.
Message Reuse Detection:

The system checks if a newly sent message already exists in the database.
If a message is found to be a duplicate, a prompt is generated to notify that the message is already present in the database.
This feature prevents the unnecessary re-storage of identical messages and enhances the efficiency of message management.
Encryption and Decryption:

Encryption: Messages are encrypted using the AES algorithm before being saved. AES provides robust security by employing a symmetric key encryption approach.
Decryption: When retrieving messages, they are decrypted to ensure that they can be read in their original form.
Advantages:

Security: AES encryption ensures that messages are securely transmitted and stored, protecting them from unauthorized access.
Efficiency: By checking for duplicate messages, the system reduces redundant data storage and improves performance.
Use Case: This project is particularly useful in scenarios where secure communication and message tracking are crucial, such as in private messaging systems, secure data storage applications, and network security solutions.
