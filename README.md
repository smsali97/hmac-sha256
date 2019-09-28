# Output Screenshots

![](C:\Users\smsal\Drive\Projects\sha_mac\2.png)

![3](C:\Users\smsal\Drive\Projects\sha_mac\3.png)

# Key Generation for HMAC-SHA256

![](C:\Users\smsal\Drive\Projects\sha_mac\1.png)

For generating the key we first used the appropiate algorithm (in this case it was SHA-256) and then on the basis of the shared private key which given to both client and server we generated HMAC and then represented a 64 Base encoded hash. This hash which was a string was to be exactly the same since both client and server had the secret key and message and could validate that indeed the message was not tampered. 