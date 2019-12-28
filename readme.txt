Copyright (c) 2014 Qvalent Pty Ltd.

Qvalent PayWay Cards API for PHP
================================

1. Requirements

PHP 4.0.6 or higher is required.  You must install the libcurl and openssl packages for PHP.
See http://www.php.net/manual/en/ref.curl.php
and http://www.php.net/manual/en/ref.openssl.php

2. Using the Example Code

2.1 Copy the "Qvalent_PayWayAPI.php" file and the contents of the 
"examples" directory to your web directory.

2.2 Login to your PayWay facility and download your certificate, save it to your server.  
Record this location for use in the initialisation of the Qvalent_PayWayAPI object.  
Update this value in the processCard.php file.

2.3 Copy the cacerts.crt Certificate Authority file to a secure location on your 
server.  Record this location for use in the initialisation of the 
Qvalent_PayWayAPI object.  Update this value in the processCard.php file.

2.4 Choose a log directory and ensure that your web application can write to that
directory on the server.  Use this location in the initialisation of the 
Qvalent_PayWayAPI object.  Update this value in the processCard.php file.

2.5 Enter your PayWay API username and password in the processCard.php file.

2.6 Using your web browser, browse to index.htm, then press the Process Capture
button.  You should receive a successful response from the Qvalent payment server.

2.7 If you receive a QI response code, then a client side error has occured. Use the 
logging setup in step 2.4 to assist debugging your configuration.
