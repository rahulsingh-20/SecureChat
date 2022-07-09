# SecureChat - A way to keep your personal information safe while chatting online

A secure chat application made with Node.js, React.js, Socket.io and Express.

## How it works

A secret key is created and stored in the frontend for demonstrational purposes.
Whenever a user sends or receives a message, the message will be encrypted/decrypted using an aes256 npm package with the same secret key.