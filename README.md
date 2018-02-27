# MpesaCI
This is a codeigniter library to process Mpesa Trasactions directly without use of any payments which would make trnsactions expensive and at times eefective. It will be soon ported to Pure Php and other Languages/Frameworks
Reference is greatly made to safaricom Mpesa PhP SDK https://github.com/safaricom/mpesa-php-sdk/.

To use the following library you must have the following : 
	A server (you can acquire one from providers usch as google, digital ocean or aws) or you can use localhost but make it publicly using tools such as Ngrok.
	Ensure curl is enabled in your server.
	Get Lipa na Mpesa Keys from safaricom developer portal. If at development also get test credentials from the same.

Set these in your application/config/mpesa_ci.php
Use them in your controllers!
