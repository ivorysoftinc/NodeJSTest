# NodeJSTest
NodeJS Test Task 

General Task
Encrypted socket chat

1. Create a backend which allow secure and instant communication between 2 clients.
2. Create a page with a list of messages and possibility to send a message and receive a message.
3. Encryption should be done in simple way:
 a) hardcode encryption key on client `TEST`
 b) On message send - encrypt message text with key `TEST` for encryption please use AES encryption `CryptoJS.AES`
4. Communication between clients MUST be made in a WEB Socket way.
5. Once client received message - decrypt it and show on page.
