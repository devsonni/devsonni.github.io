---
date: "2022-03-05"
external_link: ""
image:
  caption: Photos by Hiten Patel
  focal_point: Smart
links:
slides: ""
summary: I was team leader of the winning team in the **Robofest2.0** competition under the powered lower-limb exoskeleton category. The competition was a **state-level** competition, and teams from **tier-1** universities such as **SVNIT, Nirma University, BVM, and more** participated. Click and find more details regarding the competition and our project.  
tags:
- Rehabilitation Robotics
- Mechanical & Mechatronics Design 
- Control Systems
title: Powered Lower Limb Exoskeleton
url_code: https://github.com/devsonni/Powered-Lowerlimb-Exoskeleton
url_pdf: https://github.com/devsonni/Powered-Lowerlimb-Exoskeleton/blob/main/Pdf/Powered%20Exoskeleton%20-%20ITM%20Vocational%20University.pdf
url_slides: https://drive.google.com/file/d/1UiS9KuFzgWpcNpdP616V2AENGmsnLGZb/view?usp=sharing
url_video: "https://youtu.be/J-kVJl1uBLg"
---
---------------------------------------------------------------------------------------------------------------------------
{{< youtube J-kVJl1uBLg >}}

---------------------------------------------------------------------------------------------------------------------------    

## **This project was built for the ROBOFEST2.0 competition which was organized by GUJCOST (Gujarat Council On Science and Technology)**
     
### Competition was conducted in three rounds:
1. Idealization round (won **50,000 INR** for presenting solid ideas for building an exoskeleton robot & for building proof of concept).           
2. Proof of concept round (won **2,00,000 INR** for building a proper working proof of concept & for building the final prototype).   
3. Finale (won **5,00,000 INR** ~ 6,600 USD as a **winning prize**).
4. In short, we avail a total of **7,50,000 INR** in this project.


### Technical Details     

- Human gait trajectories were analyzed & plotted with the use of [**kinovea**](https://www.kinovea.org/) software.
- Torque requirements of each lower-limb joint were calculated with the use of the musculoskeletal model in [**OpenSim**](https://opensim.stanford.edu/) software.
- According to torque requirements **DC planetary geared motors** were selected and **spur gears** were designed.
- Whole-body with the gears was designed in **SolidWorks**.
- Six proportional derivative and integral (**PID**) controllers were coded on **Arduino** micro-controller in a way that follows the angle inputs and feedback was given by **encoders**.
- All system parameters such as PID constants, speed of exoskeleton &, etc. was tuned by trial and error method.

### Currently, Robot is showcasing at India's first & only Robotics gallery in Ahmadabad, Gujarat.
### Watch the linked video to see the robot working.