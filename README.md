# SQUEAK MOUSE

Welcome to my repository for the **Squeak Mouse**, built as part of the Hack Club Stasis! 

---

## About the Project & My Learning Journey

I decided to build the Squeak mouse because I wanted to challenge myself and dive into the world of hardware engineering and 3D modeling. Before starting this project, I was a complete beginner. I had absolutely zero experience with CAD software, and facing a professional platform like Onshape for the first time was incredibly intimidating.

The journey wasn't easy. I many hours over four consecutive days trying to decipher the instructions, sitting in front of the screen for 9 hours every single day. At the beginning, I felt completely stuck and couldn't even select the inner regions of my sketch because the software was fracturing the geometry around the imported PCB. There were moments when I felt overwhelmed by how complex the instructions seemed.

However, through sheer perseverance and step-by-step problem-solving, everything started to click. During this intense process, I mastered critical CAD concepts and workflows:
* **Feature Management:** Learning how to manipulate the features list and hide internal components (like the PCB and scroll wheel) to unblock sketch regions.
* **Parametric Constraints:** Utilizing tools like `Use / Project` to align my sketches perfectly with preexisting geometry.
* **Advanced Extrusions:** Working with symmetric extrusions (`Extrude Add` and `Extrude Remove`) to create complex internal structures.
* **Mechanical Design:** Understanding the physics of button placement and applying `Fillet` operations to eliminate mechanical stress points so the 3D-printed plastic won't snap after thousands of clicks.

This project taught me that engineering isn't just about drawing lines or following a recipe; it's about resilience and learning how to debug your design when the software throws red errors at you. I am incredibly proud that after all this effort, my final button wedges aligned flawlessly with the PCB microswitches down to the exact millimeter!

---

## 🛠️ Design & Features

The Squeak mouse body was modeled from scratch using Onshape, following a linear, structured workflow:
1. **Shelling the Enclosure:** Transformed the solid mouse body into an ergonomic, hollow shell with a uniform wall thickness.
2. **Wheel Clearance:** Created a precise top cutout to ensure the scroll wheel can rotate freely without rubbing against the plastic.
3. **Symmetric Button Clickers:** Designed integrated internal wedges directly above the mechanical switches, dividing them into independent left and right clickers using symmetric cuts.
4. **Stress Relief:** Applied a 0.5mm fillet to the internal corners of the clicker relief cuts to prevent material fatigue and optimize the model for 3D printing.
5. **Base Connection:** Prepared the bottom rim of the mouse for a 2mm base extrusion to seamlessly snap-fit the lower base plate.

---
