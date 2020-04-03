# Valkyrie

Valkyrie is a Robot that can cooperate in hospitals with the doctors and nurses to bring Medicine, Cloths, Food for Patients and also Surgical Instrument to the doctors.

## Use Cases 

* **First Phase**
  * move from one source to one destination. Curve and straight line driving.
  
* **Second Phase**
  * It will automatically open security based locked door. 
  
* **Third Phase**
  * It will automatically call and rides elevators. 
  
* **Fourth Phase**
  * Carry and move specified loads
  
* **Fifth Phase**
  * Speed control function to control the speed in different situation or on different roads..e.g. increase speed if it is an emergency
  
* **Sixth Phase**
  * Voice feedback: Hello i am Valkyrie..now i am assigned to you as your caregiver or ???? job.
  
* **Seventh Phase**
  * Additional ability to clean hospital floors (wet or dry vacuum)
  
* **Eighth Phase**
  * Add Display, that will show humidity,temperature of Environment and Destination name,Product list
  
* **Ninth Phase**
  *  Add Coffee Maker   
  
* **Tenth Phase**
  *  Ability to spray antiviral drugs or something
  
* **Eleventh Phase**
  *  Thermal scanning capability to measure human body temperature

* **Final Phase**  
  *  We will try to make Valkyrie Slim.

* **Overview of Valkyrie Hospital Robot construction**  
  *  There will be three sections in the construction

     1.Drive Unit: In the drive unit there will be some motors with wheels, suspention if needed, motor driver, microcontroller(esp32) and other electronics parts.

     2.Navigation: For navigation we will use laser sensor for sens the environment. For processing the data we will use NVIDIA TEGRA X1/X2/XAVIER.

     3.Load pick-up, Drop-offs: Basically this part is all about the mechanical things. For pickup we can use hook or something like that can pick loads. And also we will need a microcontroller.

* **Overview of Outdoo-Dron construction**  
  *  There will be five sections in the construction

     1.Drive Unit.

     2.Environment Sense.

     3.Embedded System.
      
     4.Landing - Take-off.

     5.Mechanical.
     
     
* **Motor Sizing For Val:
     As we want to use VDC motor. We have 125W VDc motor in emppapst. The model of the motor is VDC-49.15
     
     Feature of VDC-49.15:
     1. Power=125W 2.Weight=0.59Kg 3.Voltage required=48V 4.Current Required=3.2A 5.Torque=300nMn 6.rpm=400 -min
This motor is much light weight and less expensive and higly reliable.
     But if we want to carry 150kg load(include EV weight) we will need 123Nm torque. To get this torque we can use gearhead. And ebmpapst also provides some gearhead. We will use spur gearhead as it can transform huge torque.  
 
    Gearhead: Flatline 85(Spur gearhead). It can provide us (0.3*454) = 136.2Nm torque that will help us to carry up to 150kg (200kg possible) weight.

* **Positional Accuracy for Kyrie**
  * As per requirement for the Kyrie we need a High-precision Positioning and Real time data processing system. So, We have looked for different types of GPS sensors,specially the DGPS (Differential Global Positioning System) sensors which are more suitable for our Kyrie.
  * Finally, we have selected C099-F9P Application Board which allows efficient evaluation of ZED-F9P, the u-blox F9 high precision positioning module. The ZED-F9P GNSS module provides multi-band GNSS and comes with built-in RTK technology providing centimeter level (0.01m + 1 ppm CEP) accuracy to users. 
  * For powering the board we are going to use A 3.7V Li-Po Battery via a JST connector and also USB-to-DC plug adapter cable as backup.
  
  * For Communication we are going to pair a mobile phone running an NTRIP client to the C099-F9P application board using Bluetooth. 
  Another use case could be use of two C099-F9P application boards operating as Rover and Base, where the two boards communicate over a   direct Wi-Fi connection. 
  
                              * More descriptions are added in the Repo.*
  
  * Current plan: We are going to buy two application boards with two 3.7V Li-Po Battery. (other necessary items are included to the         package of  C099-F9P board)
  
  * Next Plan: Path Planning for kyrie.
  




  
  
  
  
  
