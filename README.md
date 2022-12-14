* Group Member Names: David Popa | Jade Nguyen | Pushpesh Sharma | Shyamal Singh
* Title: ElectroBoom
* Course: ECE411 Fall 2022
* Date: Oct 13, 2022
* Revision: Version 1.0

# Problem Statement and Concept of Operations
Self defense is a necessity in our everyday lives. Whether you go on late night walks in downtown or spend your time in the rural side of town, you have to be prepared to defend yourself in a attack on your person. The stun gun in its mounted state creates a non-lethal electric shock used to stop an intruder from trespassing in an unauthorized area. The device is connected to an entrance door and upon activation of the device, any unauthorized operation of the door will send an electric shock from the device to the door thus immobilizing the assailant. Although they lack some advantages, such as the capacity to render an adversary helpless or a larger range, they are highly regarded for their ease of use and accessibility. The device is mounted, its size and weight make it portable and versatile. The overall product offers a sense of security and vigilance and should be marketed as such. The final marketing team should strongly consider any number of regulations as well as the variance in stand your ground laws within the U.S and internationally. 

# Market Analysis 
As a mounted device, it can be used by a vast number of customers such as small businesses owners, street food vendors, landlords, storage units owners, RV/Van campers, etc. to protect their belongings and themselves.
Over the development of the product, it can be marketed to bigger businesses, corporate offices, banks, armored vehicles, private security firms, as well as in home security companies. 

The competition can be felt through any of the manufacturers selling pre-installed security devices as well as products that offer multipurpose use such as the Ring Doorbell etc. Our product is in a completely different region as it targets a specific audience: the self-made individuals who are vigilant and don't hesitate to do what's necessary to protect what's theirs. 
	
In comparison to other security devices and their features, our device can be priced within the $40-$50 range. There are several key factors that affect this price and as our design and overall ideas develop, the price may be adjusted accordingly. Factors like the mounting apparatus, 3D printed casing, any user interfaces used, and the cost of internal parts such as the transformer, connectors, and the PCB will eventually determine the final price for our product. 

# Product Requirements
* Must be a rugged design for versatile use and placement.
* Must send a non-lethal electric shock.
* Must be marketed as a plug in device. 
* Must not overheat. (Check transformer behavior in various situations)
* Must be operated via a Door actuated sensor. 
* Should have the ability to be deactivated via remote or physical switch. 
* Should have LED indicators to dictate state of device (Armed or Disarmed)
* May have 3D printed enclosure for all components
* May have Display to show state of device (Active, Triggered, Inactive)

# System Architecture (Currently in Design)
![Option 1](https://user-images.githubusercontent.com/115724190/196858582-5a1dcb22-82a2-43b2-aa61-d16b79606474.png)
![Option 2](https://user-images.githubusercontent.com/115724190/196858609-91594342-48de-4b04-a257-43f4444c5be2.png)

# Design Specification
* Sensor: Door knob movement actuating motion sensor, metal contact to send electric shock
* Processor: ATMega328P microcontroller with Arduino IDE for processing motion sensor activity to send electric shock via transformer. Firmware used will be the Bootloader.  
* Actuator: High voltage transformer taking input voltage and sending converted voltage at variable frequency chosen shock apparatus. 
* Power: 9V wall adapter feeding a high voltage transformer 

# Breadboard Prototype
![image](https://user-images.githubusercontent.com/115689153/199646462-8e9b4bc8-24c1-4714-a9c9-f2159e9374ba.png)
![image](https://user-images.githubusercontent.com/115689153/199646475-9283b2f0-f506-44e4-b32a-27f7112a0dc9.png)

 As seen from pictures above, the prototype is about finished and all that is needed to have a fully working prototype is the transformer (parts on their way). Image 1 shows the green LED on while the two door sensors are attached, this indicates that the system is armed and ready to go. In the second image, a red LED is shown, meaning that the door has been triggered and the voltage would be discharged out of the two open prongs that would be if the transformer parts were obtained. The video below shows the working prototype.
 
 Current status 11/02/2022: We are awaiting the arrival of our 3.3V to 2000V transformer, upon arrival, we will assemble, test, and commit this transformer to our circuit. Along with this transformer, we will run tests to ensure that the voltage and current combinations will be safe for human contact, however, it is still reccomended that all testing be done by non-human contact, for the safety of our staff, faculty, and students. 

https://user-images.githubusercontent.com/115689153/199646965-d1418cc2-3406-4b21-8939-66e534c145ff.mov

# License
GNU General Public License v2.0
The GNU GPL is the most widely used free software license and has a strong copyleft requirement. When distributing derived works, the source code of the work must be made available under the same license. There are multiple variants of the GNU GPL, each with different requirements.

See Documentation file in this repository for all sources used for this project
