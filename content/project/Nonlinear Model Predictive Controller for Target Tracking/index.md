---
date: "2021-12-31"
external_link: ""
image:
  caption: Photo by Dev Soni
  focal_point: Smart
links:
summary: Nonlinear Model Predictive Controller (NMPC) implemented with the use of **CasADi** optimization framework and matlab simulation environment. Controller is able to avoid **Static & Dynamic** **Obstacles** also **State and Control Constraints** of UAV and gimbal was added to make problem realistic.
tags:
- Control Systems
- Optimal Control
title: Nonlinear Model Predictive Controller for Target Tracking
url_code: https://github.com/devsonni/MPC-Implementation
url_pdf: ""
url_slides: ""
url_video: will add soon
---



# NMPC Implementation 🕹️     

👉 For simple intiution Model predictive control uses the system model to do prediction of future states of system for some predicted optimal inputs in prediction horizon, and applys only one input and does the same process again to compansate the unmeasured noise or disturbance in system.      
👉 In this instance our system is unmaned arieal vehicle and it's following the target which is mobile vehicle.       
👉 The cost function that sould be minimize for predicted inputs is made by the distance between UAV and target which is moving.   
👉 This code uses the CasADi framework to code NMPC.

✨ "State predictive model of target" folder of repository has the targets model which feds for the UAV as reference(a moveing reference) and it gives the cost value from the initial point of UAV.      
✨ "NMPC_TT" has the code of NMPC.      

## ✈️ UAV tracks the target illustration 🔥      

### 📌 UAV without Gimbal      

{{< figure src="TrackWTG1.jpg" caption="UAV Traking Target without Gimbal" numbered="true" >}}
           
{{< figure src="TrackTWG.jpg" caption="UAV Traking Target without Gimbal" numbered="true" >}}
   
##          

### 📌 UAV with 3-DoF Gimbal         
{{< figure src="TargetTrack6.jpg" caption="Smooth Tracking with Gimbal" numbered="true" >}}
        
{{< figure src="TargetTrack5.jpg" caption="Smooth Tracking with Gimbal" numbered="true" >}}
        
{{< figure src="TargetTrack3.jpg" caption="Smooth Tracking with Gimbal" numbered="true" >}}
      

## 🏢🏗️ Without Obstacle Avoidance      
{{< figure src="Obstacle2.jpg" caption="Without Obstacle Avoidance (UAV is Colliding with Obstacles)" numbered="true" >}}

## 🏢🏗️ With Obstacle Avoidance       
{{< figure src="Obstacle3.jpg" caption="With Obstacle Avoidance (Avoiding Collusion with Obstacles)" numbered="true" >}}
        
{{< figure src="obstacle5.jpg" caption="With Obstacle Avoidance (Avoiding Collusion with Obstacles)" numbered="true" >}}


### 🔗 This code is source code of this paper 📝        
[NMPC-based UAV 3D Target Tracking In The Presence Of Obstacles and Visibility Constraints](https://ieeexplore.ieee.org/document/9476710)       



<!-- 
First           | Second
----------------|----------------------
<img align="left" height="500" width="600" src="https://github.com/devsonni/MPC-Implementation/blob/main/gif/TargetTrack6.jpg">|<img align="left" height="500" width="600" src="https://github.com/devsonni/MPC-Implementation/blob/main/gif/TargetTrack6.jpg"> -->
