---
title: "Panthrax"
author: "Kiyan"
description: "RC Car!"
created_at: "2025-07-03"
---

## **Day 1** (06/26/2025)

* Did research on how RC Cars work!  
  * Compared motors based on KV and found out about RMPS!  
  * Found out 3650 3900KV motors are good for short bursts and good midrange RPM  
  * Decided on the Surpass Rocket 3650 3900KV motor with a 60A waterproof ESC (Took so long to find on Aliexpress!!!!)
* Picked Sakura D5 chassis, which already has 90% of everything I need, which will reduce costs! 
* For the receiver, went with the Flysky FS-iA6B since I already have a compatible transmitter   
* On the battery side of things, I decided on a dual 5200mAh 4S HOOVO would be perfect!  
  * Side note: This thing will be FFFFFFFFFAAAAAAAAAAAAASTTTTTTTTT!!!!!!!  
* Finalized BOM and added everything to my cart to get an idea of the real-world cost  

---

## **Day 2** (06/27/2025)

* Started to model the RC Car body to be aerodynamic
* Made the rough sketch of where the wheels go and the front and rear bumper
* Extruded the sketch to 130 mm, which is perfect for a 1/10 RC Car

Rough sketch!
* ![image](https://github.com/user-attachments/assets/9641a3b4-8e4b-49a0-a6f1-d640e5a91c28)

Finally extruded! 
* ![image](https://github.com/user-attachments/assets/717bb177-f4e8-47ad-b8b7-11745bee2184)

---

## **Day 3** (06/28/2025)

* Refined the Fusion 360 model  
  * Added cutouts for ESC cooling and slots to run 12AWG wires  
  * Designed custom 3D-printable motor mount plate to adjust pinion angle  
* Measured actual dimensions of motor + ESC from datasheet and scaled everything in CAD  
* Created mounting holes for RX and tiedown slots for zip-ties  
* Experimented with TPU bumper design to absorb front-end crashes  
* Started slicing components to 3D print the ones I can (battery tray, bumper, wire clamps)

---

## **Day 4** (06/29/2025)

* 3D printed the first version of the front bumper and wire clamps  
  * Print settings:  
    * Nozzle: 215 °C (TPU)  
    * Bed: 60 °C  
    * Infill: 40%, pattern: cubic  
    * Speed: 30 mm/s  
* Noticed a warp in the tray—need to reprint with a raft  
* Ordered some M3 brass inserts for frame mounting (I’ll be heat-pressing them into PLA)  
* Finalized placement of all components on chassis mockup—everything fits!  
* Tested ESC firmware options—might flash a custom throttle curve later

---

## **Day 5** (06/30/2025)

* Printed v2 of the battery tray—this time it fits and doesn't flex  
* Finished wiring plan:  
  * ESC -> motor = 14AWG silicone  
  * Battery leads = 12AWG  
  * All connectors XT60  
* Started working on a GitHub readme and folder for STL files, wiring diagrams, and future test logs  
* Looked into telemetry—might add an RPM and ESC temp sensor next week  
* Also considering making a detachable FPV mount on top 😏

---

## **Day 6** (07/01/2025)

* Modeled FPV camera mount and integrated it into the canopy  
  * Kept it low-profile to reduce drag  
* Finalized the gear mesh settings for the 3900KV motor  
* Calibrated ESC for throttle range  
* Hooked everything up for a bench test and everything spun up fine (no magic smoke thank god)  
* Still waiting on the wheels + tires to arrive—test drive probably on Day 8  
* Cleaned up wiring and zip-tied all loose wires  
* Solder joints are 🔥 — might as well call me the iron whisperer

---

## **Day 7** (07/02/2025)

* Bolted everything to the chassis for the final dry fit  
* Added foam tape to secure the batteries better and absorb vibrations  
* Reprinted one wire clamp because I broke it tightening it down  
* Documented full BOM with links and prices  
* Final AliExpress cart (with shipping + taxes): **$327.77**  
* Added part images, wiring diagrams, and CAD shots to GitHub  
* Wrote this whole log because I finally had time lol  

---
