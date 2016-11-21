# FriendsClassProject

You'll need the Arduino IDE, which you can grab here: https://www.arduino.cc/en/Main/Software, open the Arduino IDE, open the .ino file, tweak it to your liking, then run the Python server so the SMS's can be sent to your phone. 

Class projected I did for a friend, that sends an SMS when motion is detected via a PIR sensor. I chose to use the Zang.io API. If you have an Arduino UNO and a PIR sensor, this could be fun, simple run instructions, open terminal 

<pre>chmod u+x classproject.py
python classproject.py</pre>

The only issues I've had are the intervals of when the SMS's are sent, but I'm fixing this. Some of this code is about ~2 years old, with some updated code from myself. This should work with almost any Arduino. 
