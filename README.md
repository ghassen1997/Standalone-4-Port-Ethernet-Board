# Standalone-4-Port-Ethernet-Board

# Project Descreption : 

* **Function:** The Device is a networking device used to connect multiple devices on a local area network (LAN). It operates at speeds of 10/100 Mbps, allowing for efficient data transfer between connected devices. This module was developed as part of a freelance project For over 40 hours.
* **Development:** This module was developed as part of a freelance project over a 40 hours using Altium Designer. The project followed an agile approach, involving close collaboration with clients at each step to ensure verification and validation against the requirements.

* **Design Process:**
    1. **Requirement Analysis:** We begin by analyzing the client's functional and design requirements.
    2. **System Definition:** A block diagram is created to define the system and its subsystems, illustrating their interactions.
    3. **Schematic Capture:** The block diagram is elaborated on using components from an existing library.
    4. **Board Design:**
       * **Stack-up and Impedance Control:** The layer stack-up and impedance control for the Ethernet Signals that are defined.
       * **Component Placement:** Components are placed on the board considering available space based on client requirements and design rules.
       * **Rule Definition:** Define rules including manufacturer specifications and clearances outlined in IPC standard 2221.
       * **Layout:** Connect all the signals ensuring Proper clerances and Rule Respect .
       * **Design Improvement:** The design is reviewed and improved for optimal performance.
    5. **Output Files:** All necessary documents for board manufacturing are generated, including the design files and relevant documentation.
    6. **Client Delivery and Feedback:** Deliver the project to the client and Receive feedback.

  
  

The service begins with analyzing the functional and design requirements provided by the client. We then proceed to create a block diagram that defines the system and its subsystems, outlining how they will interact. Next, we elaborate on the schematic using components from an existing library. Following this, we define the layer stack-up and impedance control for the Ethernet board and Then We starting by the components Placement Regarding the avalible space Provided From the Requiement of the Client and the the layout was done regarding the Degign Rule  that already defined  Regarind manufacturer Rules and Clerance Regarding IPC standard 2221  after that we finish by the Design improvement and Board Outline and We generate the Output Job files include all the necessary Documents for the client To manufacturer the board 




 # DESIGN REQUIREMENT: 

* 5V Power Supply Input.

* The LAN Transformers can be placed on the bottom side. LAN Transformer is Low-Profile Abracon ALANL100X1-DE12DT or equivalent.

* PCB shall be 4-Layers and follow the KSZ8795 PCB Layout guide lines.

* ETH 1-4 are Molex Picoblade 4-pin Vertical connetors.

* LEDx_0 = Orange; LEDx_1 = Green.

* Add ETH Port ESD Protection: SP3051-04HTG.

* Top and bottom edge clearance: 1.5mm.

* 4x M2 Mouting Holes with 4.5mm screw head shall be integrated.

* PCB size is Fixed on 60x40m or less.

<p align="center"><img src="https://github.com/ghassen1997/Standalone-4-Port-Ethernet-Board/blob/main/Assets/Ethernet%20Switch.PNG" width="400" heigth="300"/></p>

 # LAYOUT IMPLEMENTATION : 

 * The layout has been completed in four layers (top layer, ground layer, power layer, and bottom layer), as shown in the pictures below : 

| TOP LAYER             | BOTTOM LAYER |
:-------------------------:|:-------------------------:
![](https://github.com/ghassen1997/Standalone-4-Port-Ethernet-Board/blob/main/Assets/Top%20Bottom.PNG)  |  ![](https://github.com/ghassen1997/Standalone-4-Port-Ethernet-Board/blob/main/Assets/Bottom%20Layer.PNG)

| GROUND LAYER              | POWER LAYER |
:-------------------------:|:-------------------------:
![](https://github.com/ghassen1997/Standalone-4-Port-Ethernet-Board/blob/main/Assets/Ground%20Layer.PNG)  |  ![](https://github.com/ghassen1997/Standalone-4-Port-Ethernet-Board/blob/main/Assets/Power%20Layer.PNG)


 # PCB 3D VIEW  : 

* The next pictures represents the 3D View from the Board taken From Altium Designer :

| TOP 3D VIEW             | BOTTOM 3D VIEW |
:-------------------------:|:-------------------------:
![](https://github.com/ghassen1997/Standalone-4-Port-Ethernet-Board/blob/main/Assets/TOP%203D%20VIEW.PNG)  |  ![](https://github.com/ghassen1997/Standalone-4-Port-Ethernet-Board/blob/main/Assets/Bottom%203D%20View.PNG)


 #  Real View of the Board After Fabrication and Assembly

* The pictures below show the PCB board after the fabrication and assembly process:

<p align="center"><img src="https://github.com/ghassen1997/Standalone-4-Port-Ethernet-Board/blob/main/Assets/Real%20Board%20View%203D%20(1).jpg" width="600" heigth="400"/></p>


# TEST THE ETHERNET SWITCH BOARD

* The Test Starting by taking the input of power supply 5V to the board and than connect  the switch Ethernet 1 and the Ethe Switch Ethernet 3 


 
The video demonstrates the successful data transmission of the Ethernet switch, achieving speeds up to 37.64 MB/s. Additionally, it shows the activity of the Ethernet LEDs:

* Speed LED: The orange LED indicates the current link speed.
 
* Acknowledgment LED: The green LED signifies active data transmission and acknowledgment.

* The red LED indicates the successful delivery of power supply.

> [!NOTE]
>  The board was tested by a team from LABJOY, whose testing service falls outside the scope of the work being dealt with.




[<img src="https://github.com/ghassen1997/Standalone-4-Port-Ethernet-Board/blob/main/Assets/Cover_Vedio.PNG" width="50%">](https://github.com/ghassen1997/Standalone-4-Port-Ethernet-Board/blob/main/Assets/Vedio%20Demonstration.mov)


# Customer Feedback 

The service was completed and successfully delivered. The customer has provided their feedback and shared their review regarding the work that was done, as demonstrated below :


<p align="center"><img src="https://github.com/ghassen1997/Standalone-4-Port-Ethernet-Board/blob/main/Assets/Client%20Feedback.jpg" width="400" heigth="600"/></p>





