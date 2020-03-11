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

* **Final Phase**  
  *  We will try to make Valkyrie Slim.

* **Overview of Valkyrie Hospital Robot construction**  
  *  Thre will be three section in the construction

     1.Drive Unit: In the drive unit there will be some motors with wheels, suspention if nidded, motor driver, microcontroller(esp32) and other electronics parts.

     2.Navigation: For navigation we will use laser sensor for sens the environment. For processing the data we will use NVIDIA TEGRA X1/X2/XAVIER.

     3.Load pick-up, Drop-offs: Basically this part is all about the mechanical things. For pickup we can use hock or something like that can pick loads. And also we will need a microcontroller.

* **Overview of Outdoo-Dron construction**  
  *  Thre will be five section in the construction

     1.Drive Unit.

     2.Environment Sense.

     3.Embidded System.
      
     4.Landing - Take-off.

     5.Mechanical.
     
     
* **Motor Sizing For Val:
     As we want to use VDC motor. We have 125W VDc motor in emppapst. The model of the motor is VDC-49.15
     
     Feature of VDC-49.15:
     1. Power=125W 2.Weight=0.59Kg 3.Voltage required=48V 4.Current Required=3.2A 5.Torque=300nMn 6.rpm=400 -min
This motor is much light weight and less expensive and higly reliable.
     But if we want to carry 150kg load(include EV weight) we will need 123Nm torque. To get this torque we can use gearhead. And ebmpapst also provides some gearhead. We will use spur gearhead as it can transform huge torque.  
 
    Gearhead: Flatline 85(Spur gearhead). It can provide us (0.3*454) = 136.2Nm torque that will help us to carry up to 150kg (200kg possible) weight.





  
  
  
  
  
