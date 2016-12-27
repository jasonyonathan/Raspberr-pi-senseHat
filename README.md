# Raspberry-pi-senseHat
An advanced way of using senseHat sensors by selecting them through the on-board joystick

To Start a Demo

*)Deploy the UWP app to your raspberry pi (attached with senseHat)

*)Choose the sensors using the joystick (Left->Temperature , Right->Humidity , Down->AirPressure , Enter->Scrolling Text)

*)Have Fun :v :)



# What's inside the code ?
In this project, I am using the emmelsoft Raspberry Pi SenseHat libraries (https://github.com/emmellsoft/RPi.SenseHat)...
in the same solution, i made a new project called RPi.SenseHat.Test..
in the MainPage.xaml.cs, i called the home selector class which connected to the home.cs class. inside the home class, the raspberry pi will read the joystick values and called another action based on the joystick selection.

Once the action is selected, it will run the sensor command and display the values on the led matrix and after 2s, back to the home.cs and we can call another Action selection

for full information about senseHat and it's connection to the Windows 10 IoT, you can access these links below:

https://github.com/emmellsoft/RPi.SenseHat

https://www.raspberrypi.org/products/sense-hat/

hope this project is helpful for you :)
