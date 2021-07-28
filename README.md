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

I am uploading screenshots and pictures of the connections. 

![WhatsApp Image 2021-07-28 at 11 09 16 (1)](https://user-images.githubusercontent.com/80844300/127270558-ebd2fd57-ce8c-4dbe-a6f4-6a7e295854fe.jpeg)
![WhatsApp Image 2021-07-28 at 11 09 16 (2)](https://user-images.githubusercontent.com/80844300/127270550-85abcbcc-7274-4986-81c9-d46b6c1c6378.jpeg)
![WhatsApp Image 2021-07-28 at 11 09 16](https://user-images.githubusercontent.com/80844300/127270562-f90f7fbf-3817-4005-b995-ecc47d619cf4.jpeg)
