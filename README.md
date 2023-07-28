# Robot_ESP32
Task 1 of the Internet of Things path
***


## What is ESP32
ESP32 is a single 2.4 GHz Wi-Fi and Bluetooth combo chip designed with the TSMC low-power 40 nm technology. It is designed to achieve the best power and RF performance, showing robustness, versatility, and reliability in a wide variety of applications and power scenarios.

ESP32 is a better and more powerful microcontroller board than Arduino. ESP32 has inbuilt dual Wi-Fi and Bluetooth support. It has full TCP/IP support for a full-stack internet connection. Thanks to its Wi-Fi module it can act as an access point as well as a Wi-Fi station.



## Applications of ESP32
* IoT smart electricity energy meter
* Smart home controller
* Indoor air quality analysis
* Security Systems such as access control systems, alarm systems, and surveillance cameras




## How the code works
In the void setup() function, the wifi connection is requested from the host, then pin modes are defined as output (LEDs). In the void loop() function, an HTTP request is made from the URL defined at the beginning of the code that includes the page that will show the result. Then, a variable named payload is defined to store the text from the defined URL. Within the loop function, an if-else-statement is made to turn on the LED if the chosen URL contains the desired text or not.


Turn on the green LED if the URL contains the word "forward"
![Forward Page](https://github.com/iidabawaj/Robot_ESP32/assets/139181626/b1f5eafe-b8ca-4085-8ac5-27d816cc1ff2)


Turn on the yellow LED if the URL contains the word "backward"
![Screenshot (416)](https://github.com/iidabawaj/Robot_ESP32/assets/139181626/107ee0c3-9dd0-4808-a940-a927a5b350d8)


Turn on the blue LED if the URL contains the word "left"
![Left Page](https://github.com/iidabawaj/Robot_ESP32/assets/139181626/3afce23e-11f3-4c1b-99ce-c1e8ca19128e)


Turn on the pink LED if the URL contains the word "right"
![Right Page](https://github.com/iidabawaj/Robot_ESP32/assets/139181626/75186bad-e311-49ac-999b-f4fd0f4c4e6f)


Turn on the red LED if the URL contains the word "stop"
![Stop Page](https://github.com/iidabawaj/Robot_ESP32/assets/139181626/c920672a-ad4c-412c-b24e-ea2577457bd1)

