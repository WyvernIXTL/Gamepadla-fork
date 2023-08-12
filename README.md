# Gamepadla
Gamepads latency tester and polling rate program  
Based on the method of Christian P.: https://github.com/chrizonix/XInputTest  
Pyhon code written by John Punch: https://t.me/ivanpunch

     ██████╗  █████╗ ███╗   ███╗███████╗██████╗  █████╗ ██████╗ ██╗      █████╗
    ██╔════╝ ██╔══██╗████╗ ████║██╔════╝██╔══██╗██╔══██╗██╔══██╗██║     ██╔══██╗
    ██║  ███╗███████║██╔████╔██║█████╗  ██████╔╝███████║██║  ██║██║     ███████║
    ██║   ██║██╔══██║██║╚██╔╝██║██╔══╝  ██╔═══╝ ██╔══██║██║  ██║██║     ██╔══██║
    ╚██████╔╝██║  ██║██║ ╚═╝ ██║███████╗██║     ██║  ██║██████╔╝███████╗██║  ██║
     ╚═════╝ ╚═╝  ╚═╝╚═╝     ╚═╝╚══════╝╚═╝     ╚═╝  ╚═╝╚═════╝ ╚══════╝╚═╝  ╚═╝

A website with a catalog of tested gamepads: https://gamepadla.com

ABOUT GAMEPADLA  
Gamepadla is an easy way to check the latency of your gamepad. This tool will help you get accurate data about your controller's performance, which can be useful for gamers, game developers, and enthusiasts.  
Gamepadla works with most popular gamepads and supports DInput and XInput protocols, making it a versatile solution for testing different types of controllers.  

DISCLAMER  
Gamepadla measures the delay between successive changes in the position of the analog stick on the gamepad, rather than the traditional input latency, which measures the time between pressing a button on the gamepad and a response in a program or game.  
This method of measurement can be affected by various factors, including the quality of the gamepad, the speed of the computer's processor, the speed of event processing in the Pygame library, and so on.  
Therefore, although Gamepadla can give a general idea of the "response" of a gamepad, it cannot accurately measure input latency in the traditional sense. The results obtained from Gamepadla should be used as a guide, not as an exact measurement of input latency.  

Here's how to use Gamepadla:  
1.  Connect your gamepad to your PC.  
    You can connect your gamepad via Bluetooth, with a cable, or with the included receiver. Make sure your operating system recognizes the gamepad.  
2.  Launch Gamepadla.  
    Just double-click on the fileGamepadla.exe filefile to launch the program.  
3.  Check the connection of your gamepad.  
    Gamepadla will automatically detect connected gamepads. If your gamepad is not detected, make sure it is connected correctly and try again.  
4.  Run the test.  
    After the gamepad is detected, the program will ask you to move the left stick in a circle without stopping. This will allow the program to collect data about the gamepad's latency.  
5.  View the results.  
    When the test is complete, the program will redirect you to the site with the results. You will see the minimum, average, and maximum latency, as well as the polling rate and jitter.  
6.  Compare the results.  
    If you want to compare the results of different tests, simply repeat the test. The results will be added to your test page.  
