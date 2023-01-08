# arduino-non-blocking-project
This project is for the Arduino forum. I was trying to learn about how to implement non blocking. This archive is really for my own records.
See video on YouTube: https://www.youtube.com/watch?v=fKVmv6uI9n8 
Arduino forum: https://forum.arduino.cc/t/i-used-millis-to-avoid-blocking-but-somehow-it-stops-rocking/1073819 

I used a step motor as well as the HC_SR04.
If you use any of this code, I suggest you compare it to code from other more experienced programmers as I am still learning. 

// this program should have 5 tabs. Sorry I couldn't figure how how to auto create them. 
distanceWithAdds.ino  // this is where main() resides
HC_SR04_check.ino     // this checks to see if the HC_SR04 detects something within 20cm
HC_SR04_flash.ino     // this flashes the LEDS depending on what the HC_SR04 reports
setup.ino             // I moved the setup to a separate file
stepMotor.ino         // this runs constantly but, only moves the step motor if conditions are met

I also added a terrible schematic of the configuration for my own personal notes. 
