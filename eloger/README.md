For this project using any ESP8266, for example ESP8266 wemos.
https://www.google.com/search?q=esp8266+wemos+buy&oq=esp8266+wemos+buy&aqs=chrome..69i57j0i15i22i30.6848j0j7&sourceid=chrome&ie=UTF-8

All cheap modules are based on ch340/ch340g comunication IC, and they need drivers for proper work, find one:
https://www.google.com/search?q=ch340+driver&ei=G_WYY7GWHNWbwPAPquGMsAg&ved=0ahUKEwjxj6mQy_f7AhXVDRAIHaowA4YQ4dUDCA8&uact=5&oq=ch340+driver&gs_lcp=Cgxnd3Mtd2l6LXNlcnAQAzIECAAQQzIFCAAQgAQyBQgAEIAEMgQIABBDMgUIABCABDIFCAAQgAQyBQgAEIAEMgUIABCABDIECAAQQzIFCAAQgAQ6CggAEEcQ1gQQsAM6BwgAELADEENKBAhBGABKBAhGGABQ7QRYjw9grxZoAXABeACAAWqIAcIFkgEDMi41mAEAoAEByAEKwAEB&sclient=gws-wiz-serp

Also download Arduino for uploading sketch to ESP
https://www.arduino.cc/

sketch for project can be found in this folder esp8266loger.ino
before upload plz change:
WIFIlogin - to your wifi network login
WIFIpassword -to your wifi network password
http://site.com/method - to server and method which is used to collect logs (for uphome.fun contact to developer for your own method)

There is no need in any schematic, just power module by built in esp8266 Wemos board micro usb
