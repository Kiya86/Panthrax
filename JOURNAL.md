---
title: "SkyTrack"
author: "Kiya Kesheh"
description: "100 mph FPV drone!
created_at: "2025-05-21"
---

## **Day 1** (05/21/2025)

* Did research on what components are best  
  * Compared thrust, KV, and RMP curves for multiple 5-inch prop motors   
  * Selected the:  
    *  Axisflying Bando 2207.5 1960 KV motors based on their torque and top-end RPM on 6 S  
  * Also chose a 65A 4 in 1 ESC for the motors  
    * 3065 AM32 65 A 4-in-1 ESC  
  * Compared flight controllers to see what is best and whether I should use F7 flight computers, but instead opted to use the F4 flight computer  
    * Matek F405-HDTE  
      * Has an STM32F405  
      * MPU6000  
      * Onboard OSD  
      * And built a current sensor   
  * Also did research on what propeller size I should be using and decided a 5-inch is best for a high-speed drone, so I chose:  
    * HQProp Ethix S4 5×4.5×3 tri-blades  
  * Also decided to use a 6S battery as the motors would run at max speed with it  
    * 2pcs CNHL Lipo Battery 6S 22.2V 1100mAh 1500mah 100C With XT60 For RC FPV Quadcopter Airplane Helicopter Hobby  
    *   
* Lastly made a BOM of all parts to see how much it would cost, and the exact price with tax and shipping is **$304.20**

## **Day 2** (05/22/2025)

* Made a sketch of a frame to work with the 5-inch props and made sure the center of gravity would not be messed up   
* Drew the sketch in Fusion 360 and made a 240mm diameter motor-to-motor spacing  
* Modeled the body with channels to route wires going from the ESC to the motors   
* Added other channels to hide wires   
* Added a low-profile canopy   
* Did not add mounting holes, as I will be using a soldering iron with brass inserts   
* Beefed up sections under high loads
  
Made the sketch for the drone frame 

 ![image](https://github.com/user-attachments/assets/9bc51c23-1af5-42eb-b568-c7345a81819a)
 
Did some shaping via sketches 

![image](https://github.com/user-attachments/assets/074c4626-bea5-4acc-bdd5-1d77370d2fbb)

Extended the frame to fit the props and to clear the battery 

![image](https://github.com/user-attachments/assets/c9e3b09f-4187-4bdd-8f11-810cbb9fbe60)

Making the top portion of the drone using the bottom sketch 

 ![image](https://github.com/user-attachments/assets/891914b7-18f3-4ff4-90c4-00a1278494c9)
 
Did some weight using another sketch 

 ![image](https://github.com/user-attachments/assets/6cc9bc8f-36d0-4af7-9919-9110dc38ac12)
 
Rounded corners to make it look nicer

 ![image](https://github.com/user-attachments/assets/d5fb5759-7005-47ce-ad2a-4fc3f68a7085)

## **Day 3** (05/23/2025)

* Fixed some geometry of the drone and reduced weight  
* Added more channels for battery wires  
* Started to make the GitHub repository (This was done a little later the day after (I might or might not have feel asleep))
* Added all parts to an Excel sheet and saw how much tax and shipping fees were on Aliexpress  
* Added everything to the BOM and finalized last-minute changes  
* 3D printed the frame with carbon reinforced filament (Nozzle is cooked)   
* The frame was printed at:  
  * Nozzle: 230 °C  
  * Bed: 100 °C  
  * Infill: Gyroid at 50% infill   
  * 0.2mm layers   
  * Speed: 75%   
  * Slicer: Cura

 ## **My Story** 

* Ever since I started my sophomore year of high school, I have wanted to take on a project that was ambitious. After months of brainstorming, I came up with a couple of ideas, such as building a rover, a high-speed drone, or rockets. After debating and consulting my sibling, I decided to watch videos on drone builds, and I was amazed! All of the parts available and the electronics just shocked me. How did they think of this? How was this made? After countless videos, I came up with a rough list of requirements: carbon frame, high-kv motors, all-in-one ESC, 4s lipo, lightweight, and cool paint job. After adding up the costs of all parts, I found it to be very expensive, as all parts totaled $500. This was way too much and still is way too much for my family (low income), so I decided to put the entire project to the side and build rockets instead (Way cheaper). But after getting bored of rockets, I came back to the drone project due to "highway" and decided to update the parts and reduce costs as I could reuse what I had. For example, I have a 6s lipo, so I adapted the ESC to that and got rid of the battery (4s one). The total cost for the new BOM proved to be way less, and has got me excited, as I have a plan for this drone that I will hopefully build.
* 
![image](https://github.com/user-attachments/assets/dce94e56-ea4e-4e65-9911-340b8672bb57)

![image](https://github.com/user-attachments/assets/a488a931-8043-4459-98ed-121188d9c8d2)

