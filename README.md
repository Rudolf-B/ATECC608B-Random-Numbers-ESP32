# ATECC608B-Random-Numbers-ESP32
Simple Library to obtain TRNG numbers from the ATECC608B with an ESP32.
You need to lock the device first. The easiest way to do is is by using code made by Sparkfun, You can find it here:
https://github.com/sparkfun/SparkFun_ATECCX08a_Arduino_Library 

Instal the the Sparkfun library and upload it to the ESP32. Open the Serial monitor and follow the instructions. Now The IC is ready to generate Random numbers.

Now download the TRNG library as a zip file. In ArduinoIDE go to SKETCH> Include library >  ADD .ZIP library...  and select the just dwnloaded zip folder with my library. Now you can proceed with the code!
