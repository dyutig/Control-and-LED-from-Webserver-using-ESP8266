# Control-an-LED-from-Webserver-using-ESP8266

In this project, I wanted to experiment how we can access different appliances remotely from another location. 

The steps I followed are:
1. Wrote code
   Note: Following information has to be edited from your end. ssid<- My WiFi Name. password<- The WiFi Password.
2. Make connections with ESP8266. D7 <- LED +ve pin (longer). GND <- LED -ve pin (shorter)
3. Compile and Upload code. 
4. Open serial monitor. Set 115200 baud.
5. When WiFi is connected, the message will show. Copy the content after "Use this URL to Connect:..." I copied "192.168.1.10"
6. Paste it in browser. 
7. Now on clicking "Turn On", LED turns ON and on clicking on "Turn OFF", LED turns OFF.
8. Done.

I am uploading screenshots and pictures of the connections. Please check the images folder. 
