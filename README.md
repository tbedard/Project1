# Project1
//This is just a quick and dirty program with a few flaws i will get around to fixing as i go, for the FRDM-k64 freedom dev board.

//Its design is to control a 20A ESC for a Ducted brushless fan motor.
//Pretty basic stuff here just an ESC init, than a main loop to monitor the two push buttons on the dev kit in order to increase the PWM
out to the ESC from 1200uS, to 1900uS, full off to full on. I have code in for some printF statements to let you know whats going on and 
what the PWM pulsewidth is at, you can use tera term to interface though the virtual usb port.
