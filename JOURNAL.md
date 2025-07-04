---
title: "SkyTrack"
author: "Kiya Kesheh"
description: "100 mph RC car!"
created_at: "2025-07-01"
---

## **Day 1** (07/01/2025)

* Did a ton of research on how RC cars are built  
  * Compared 3650 vs. 3665 vs. 4268 motors  
  * Found out 3650 3900KV motors are good for short bursts and good midrange RPM  
  * Decided on the Surpass Rocket 3650 3900KV motor with a 60A waterproof ESC  
* Picked an AXSPEED metal chassis because it has a solid build, and comes with 4 wheels, dampers, servo mount, and all that already  
  * Less I have to design, the faster I get to the fun part (breaking stuff and rebuilding lol)  
* For the receiver, went with the Flysky FS-iA6B since I already have a compatible transmitter  
* Battery-wise, I decided on a dual 5200mAh 4S HOOVO pack to give me the juice I need  
  * This thing will be a beast—should hit 100mph with gear tuning  
* Finalized BOM and added everything to my cart to get an idea of the real-world cost  
  * Total cost with shipping and taxes: **$327.77** 😮‍💨

---

## **Day 2** (07/02/2025)

* Modeled the full drivetrain in Fusion 360 based on wheel size and chassis layout  
  * Front and rear differential spacing adjusted to the AXSPEED chassis dimensions  
* Drew out servo and ESC placement with wire routing under the top plate  
* Designed a modular battery tray that can slide to adjust CG front-to-back  
* Looked up gearing ratios and experimented with some hypothetical values in a calculator  
  * Maxed out theoretical speed = 112mph at 85% throttle on 4S 👀  
* Still figuring out how to keep the motor cool without air ducts

---

## **Day 3** (07/03/2025)

* Refined the Fusion 360 model  
  * Added cutouts for ESC cooling and slots to run 12AWG wires  
  * Designed custom 3D-printable motor mount plate to adjust pinion angle  
* Measured actual dimensions of motor + ESC from datasheet and scaled everything in CAD  
* Created mounting holes for RX and tiedown slots for zip-ties  
* Experimented with TPU bumper design to absorb front-end crashes  
* Started slicing components to 3D print the ones I can (battery tray, bumper, wire clamps)

---

## **Day 4** (07/04/2025)

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

## **Day 5** (07/05/2025)

* Printed v2 of the battery tray—this time it fits and doesn't flex  
* Finished wiring plan:  
  * ESC -> motor = 14AWG silicone  
  * Battery leads = 12AWG  
  * All connectors XT60  
* Started working on a GitHub readme and folder for STL files, wiring diagrams, and future test logs  
* Looked into telemetry—might add an RPM and ESC temp sensor next week  
* Also considering making a detachable FPV mount on top 😏

---

## **Day 6** (07/06/2025)

* Modeled FPV camera mount and integrated it into the canopy  
  * Kept it low-profile to reduce drag  
* Finalized the gear mesh settings for the 3900KV motor  
* Calibrated ESC for throttle range  
* Hooked everything up for a bench test and everything spun up fine (no magic smoke thank god)  
* Still waiting on the wheels + tires to arrive—test drive probably on Day 8  
* Cleaned up wiring and zip-tied all loose wires  
* Solder joints are 🔥 — might as well call me the iron whisperer

---

## **Day 7** (07/07/2025)

* Bolted everything to the chassis for the final dry fit  
* Added foam tape to secure the batteries better and absorb vibrations  
* Reprinted one wire clamp because I broke it tightening it down  
* Documented full BOM with links and prices  
* Final AliExpress cart (with shipping + taxes): **$327.77**  
* Added part images, wiring diagrams, and CAD shots to GitHub  
* Wrote this whole log because I finally had time lol  

---

## **My Story**

* Back in sophomore year, I told myself I wanted to build something insane. Not just school projects. Something with speed. After playing around with drones and rockets (and destroying both, not gonna lie), I wanted something that could survive a bit more punishment. So I started thinking... what about an RC car that could hit 100mph? That’s wild.  
* The issue was cost—like always. The drone project from earlier almost made me cry with how expensive it was ($500+ easy). But with this car, I found some solid deals on AliExpress, reused stuff I already had (like LiPos), and built the rest from scratch.  
* I’ve learned more doing this in a week than I did in a month of school. CAD modeling, electronics, gear ratios, 3D printing—it’s all starting to click.  
* Whether it hits 100mph or not, I’m proud of how far it’s come. It’s not just a car; it’s a part of my brain, printed, soldered, and zip-tied together.
