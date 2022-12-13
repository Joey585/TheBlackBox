This will be my biggest project in a long time. It will include aspects of every skill that I have picked up since I ever started coding.

The project will include:
- Radio frequency transmitter
- Flipper application development with hardware included
- GPRS to http post via SIM card
- Battery management system
- Temperature monitor
- GPS antenna
- HTTP API server
- Database to store all entries
- Webserver to display all entries
- Discord bot to check mood

Languages needed:
- C (flipper app)
- Arduino
- NodeJS

**What is the black box?**

The black box is a 3d printed box with a usb-c port and 1 button

The purpose of it is to track your location every 10 minutes, send it to a NodeJS server via GPRS (2g) . The info it will send is: GPS location, temperature, speed of travel (if not 0). The server will then parse the data due to the setting I have put, then add it to the database.

The flipper part: When you click the button on the actual box, it will transmit a quick sub ghz signal meant for the flipper to decode and display on the screen. It will show the battery life, current position, and other debug stuff. It will be a custom application coded in C for the flipper to decode the signal. 

Is this inefficient? Yes.
Is it cool? Some might say yes.

I have already done a bit of research on this but nothing has been executed yet. I will be commenting all of my research and thoughts here, and you are free to yell at me or give me suggestions. 


*Inspired by* <a href="https://www.howisfelix.today">Felix</a> and Airplane Black Boxes
