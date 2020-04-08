# SSL Certificate 

Create a tutorial covering the following topics

1. Set up a webserver supporting HTTPS with perfect forward secrecy. 
   
   For the server certificate, you can use free certificates, such as the [Let's encrypt certificate][1]. Connect to the web server with your web browser and make sure that it is using the encryption mode that satisfies perfect forward secrecy. Also, please introduce the [ACME protocol][2] in your tutorial.

2. Self-signed certificate

   Generate a self-signed server certificate (i.e., you sign the certificate with your own private key) and install the certificate to *your web server* and *your web browser*. Make sure the web browser will trust the server certificate without showing any warning message on the HTTPS connection. 

3. Use man-in-the-middle to decrypt HTTPS encryption
   
   Set up a man-in-the-middle proxy (e.g., [mitmproxy][3]) to intercept & decrypt a HTTPS connectoin (e.g., a connection to www.gmail.com).  
   
   

[1]: https://letsencrypt.org/
[2]: https://en.wikipedia.org/wiki/Automated_Certificate_Management_Environment
[3]: https://mitmproxy.org/
