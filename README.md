# Cold Box Setup: A complete guide to setting up and operating the chiller
## Prepare to run the code:
1. If you haven't already, download Visual Studios (VS) for free using the link below.

          https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=Community&rel=16
          
2. Download the arduino codes. For VS to work properly, () must also be open.
   () collects the serial numbers of the thermal sensors for data collection 
   () allows VS to communicate with the arduino. 
3. Download ColdBoxControl.csproj to operate the chiller located under !!!!!!!. 
## Understanding Visual Studio
There are (3??) files below the top toolbar
  - Form1.resx
  - Form1.cs includes annotation to help read the code
          - This code can be altered to your heart's content <3
  - Form1.Designer.cs 
         - do not touch! This is automatically generated
## Operating Interface
  To see the operating interface, click on Run at the top of the screen.  
  A white box should appear on your screen. Below, I will explain the buttons as they appear from left to right. Descriptions of the buttons can also be found in the annotated code.
  
          - Chiller Serial
                    - Select port that coincides with where the chiller is connected.
                    - Click open. This opens the port and allows communication between chiller and VS             
          - Arduino Serial
                    - Select port that coincides with where the arduino is connected.
                    - Click open. This opens the port and allows communication between the Arduino and VS
                              Note: Sometimes the Arduino will randomly switch ports.
                              If you cannot communicate with the arduino, check different ports.
          - 
## Physical Setup of the Chiller
### Chiller
Chiller includes the following components
          - Styrofoam coldbox
                    - side hole for connecting ports, Arduino with sensors attached
                    - holes for inserting antifreeze pipes
                    - peltier?????
                    - coldplate that does STUFF!!!!!!
                    
### Ports
### Arduino
### Sensors
## Communicating with the chiller
