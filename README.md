# Web_BLE_ESP32_360Visualisation
A phone takes 360 pictures of an object, turned by a stepper motor.
The phone communicates with the stepper motor driven by a esp32 over web ble.
A flask web app controls everything and takes the pictures automatically and saves them locally on the PC which hosts the flask app.



## Flask needs to run on https
*Download openssl: https://slproweb.com/products/Win32OpenSSL.html
* openssl.exe req -x509 -newkey rsa:4096 -nodes -out cert.pem -keyout key.pem -days 365
*run this in C:program files/openssl/bin/*
* move key and perm files into *secure* folder





Sources:
* https://github.com/pdjstone/cloudpets-web-bluetooth 
* https://stackoverflow.com/questions/65546987/how-to-capture-images-using-opencv-and-flask
* codesandbox mediacapture for focusMode and ExposureTime
