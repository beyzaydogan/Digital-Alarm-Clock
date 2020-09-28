# Digital-Alarm-Clock
Introduction
In this project it is expected to build a digital alarm clock using an Arduino microcontroller. The clock will have different functionalities implemented in it, like showing the temperature, switching between 12H and 24H modes, setting up the values for current time and alarm time, etc. via the use of buttons.

Requirements
- LCD screen which is showing:

            1-Current time (Switchable between “00:00-24:00” and “00-12 AM/PM”)

            2-Alarm time (with a symbol indicating ON/OFF)

            3-Temperature (Switchable between Celsius and Fahrenheit)

-4 Buttons which are used for:

            B1-Switching between modes in current time

   (Hold 3 seconds for current time setup)

            B2-Setting the alarm ON and OFF

               (Hold 3 seconds for alarm time setup)

B3-Switching between temperature scales (Fahrenheit /Celcius)

   (During a value setup, this button acts as “raise value ^”)

            B4-Snooze button

               (Temporarily stops alarm for only 5 minutes)

- Piezo buzzer for the alarm sound

- Potentiometer for changing backlight brightness

- Temperature sensor for detecting temperature


 

To see which value is being set at a given time, the time value which is being set will blink.

Here is an example setup scenario of setting up alarm time:

Alarm Set Up
1-Hold B2 for 3 seconds to start setup *alarm minute will blink*

2-Use   B3 to adjust alarm minute

3-Press B2 once to switch to hour *alarm hour will blink*

4-Use   B3 to adjust alarm hour

5-Press B2 again to end setup *nothing will blink*

Clock Set Up
1-Hold B1 for 3 seconds to start setup *clockminute will blink*

2-Use   B3 to adjust alarm minute

3-Press B1 once to switch to hour *clock hour will blink*

4-Use   B3 to adjust alarm hour

5-Press B1 again to end setup *nothing will blink*
