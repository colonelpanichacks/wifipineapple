# wifipineapple
Writeup on how to access Wifi pineapple GUI through non-management APs and fuzz web app login credentials 

Summary: The WiFi Pineapple MKVII management GUI can be accessed by connecting to one of the spoofed APs
created by the PineAP, thus circumventing the use of a pre-shared key to access the
management GUI. The password to access the management GUI can then be easily fuzzed to
gain access to the management GUI. The default username used to access the GUI is “root”.
Upon further investigation, it was found that the login screen will accept any username
supplied, so long as it is paired with the correct password.

I have attached a pdf file with my writeup as a proof of concept.  
