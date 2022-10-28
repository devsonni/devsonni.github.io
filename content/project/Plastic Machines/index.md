---
date: "2020-02-27T00:00:00Z"
external_link: ""
image:
  caption: Photo by Dev Soni
  focal_point: Smart
summary: Motto behind the development of these machines is to recycle plastic waste at the place where it forms means decentralization of the recycling process, with the use of these machines a community can recycle their plastic waste; can produce robust and purposeful products. This project was supported by **SSIP (Student Start-up and Innovation Policy) of the Gujarat Government** and received **83,899 ₹** grand, and these machines are built according to Indian design standards and derivative of [Precious Plastic Community](https://preciousplastic.com/). 
tags:
- Machine Design
- Automation
- Electrical & Electronics
- Control System
title: Community Plastic Extrusion and Compression Molding Machine
url_pdf: ""
url_slides: ""
url_video: ""
---

# 🎯 Motto 
- World is filled with a plethora of waste plastics, and only ~33% of plastic gets recycled: motto behind the development of these machines is to recycle plastic waste at the place where it forms means decentralization of the recycling process, with the use of these machines a community can recycle their plastic waste; can produce robust and purposeful products.
- This project was supported by SSIP (Student Start-up and Innovation Policy) of the Gujarat Government and received 83,899 ₹ grand.

# ⚙️ Extrusion Molding Machine
---
## 🌐 3D Model
<iframe width="800" height="400" src="https://b2b.partcommunity.com/community/partcloud/embedded.html?route=embedded-viewer&name=Extrusion+Molding+machine&model_id=118643&portal=b2b&noAutoload=false&autoRotate=false&hideMenu=false&topColor=%23FFFFFF&bottomColor=%23ffffff&cameraParams=false&varsettransfer=" frameborder="0" id="EmbeddedView-Iframe-118643" allowfullscreen></iframe>


## 📓 Technical Information 

|Specification| |     
|:----------|-------------:|
|📓 Type|Single Screw|   
|💰 Price new material in INR|+/- ₹80,000| 
|⚖️ Weight (inc frame)|110 kg |
|📦 Dimension|1500 x 600 x 1550 mm|
|⚙️ Power (W)|5 kW|
|🔌 Voltage|230V|
|⚡️ AMP|16A|
|♻️ Input Flake Size|Small|  
|🔩 Screw diameter|30mm|
|🔩 Length of screw (mm)|790 mm| 
|🔩 Effective screw length|600 mm| 
|🔩 Rated Motor Power|2.2 kW| 
|⚙️ Motor Type|3 ph. 440V +/- 5%| 
|⚙️ Gearbox type|Worm gearbox - 7.5 reduction ratio| 
|Geared Motor output Torque|~163 Nm| 
|Gear shaft Output speed|192 RPM|   
|Motor shaft|28 mm|
|Heating zones|3| 
|Heating power: max.|2 kW|

## Images of Extrusion Machine

<img src="https://i.imgur.com/6WyfGpz.jpg?1" title="source: imgur.com" width ="350" height="300" align="left">

<img src="https://i.imgur.com/ZzEhEJy.jpg?1" title="source: imgur.com" width ="350" height="300" align="right">     

<img src="https://i.imgur.com/0Q5LSXk.jpg?1" title="source: imgur.com" width ="350" height="300" align="left">

<img src="https://i.imgur.com/ZzEhEJy.jpg?1" title="source: imgur.com" width ="350" height="300" align="right"> 

<img src="https://i.imgur.com/rno091s.jpg" title="source: imgur.com" width ="350" height="300" align="left">

<img src="https://i.imgur.com/a4Tojh6.jpg" title="source: imgur.com" width ="350" height="300" align="right"> 

<img src="https://i.imgur.com/hWrjUfs.jpg" title="source: imgur.com" width ="350" height="300" align="left">

<img src="https://i.imgur.com/t7EOeZh.jpg?1" title="source: imgur.com" width ="350" height="300" align="right">      
      
# ⚙️ Compression Molding Machine
---
The compression machine is basically an electric kitchen oven to heat the plastic, and a compression mechanism (a carjack) to apply pressure to your mold. The process is slower than the extrusion machines but it allows for larger molds to be used. It can be used to create raw material, like sheets or shapes that can be further worked on to make new products and gives a specific flake-like look to the plastic (which looks amazing!).

## 📓 Technical Information

📓 Type | Compression Machine
:--- | ---:
💰 Price new material in INR | +/- ₹5000
💰 Price scrap material in INR | +/- ₹3000
⚖️ Weight | 30 kg
📦 Dimensions | 500 x  590 x 1590 mm
⚙️ Compression | 5t car jack
🔌 Voltage | 230V
⚡️ AMP | 16A (3 heating coils)
♻️ Input Flake Size  | Medium, Small  |

## 🌐 3D Model
<iframe width="800" height="500" src="https://b2b.partcommunity.com/community/partcloud/embedded.html?route=embedded-viewer&name=Compression+Basic+V2.0&model_id=96647&portal=b2b&noAutoload=false&autoRotate=false&hideMenu=false&topColor=%23dde7ed&bottomColor=%23ffffff&cameraParams=false&varsettransfer=" frameborder="0" id="EmbeddedView-Iframe-96647" allowfullscreen></iframe>

## ⚡️ Electronic box
Explanation of the electric components inside this machine. More information and schematics can be found in the download-kit.

* <b>PID Controller:</b> the brains of the machine where you can set your desired temperatures. It will send power to the heaters until PV (point variable) matches the SV (set value). It does this using readings from the thermocouple and the SSR.
* <b>SSR:</b> the Solid State Relay is an electronic ‘switch’ that opens and closes depending on the signal it receives (from the PID).
* <b>Thermocouple:</b> basically a thermometer.
* <b>Band heater:</b> heating element that fits around a pipe.
* <b>Power switch:</b> mechanical switch.
* <b>Power cable:</b> common household power cable.

## 🛠 Tricks used while making

- Looked around for second hand or scrap oven, and re-wired all heating coils through SSR and PID controller.
- Insulated oven with the use of rock-wool.
- A k-type thermocouple sensor mounted inside of the oven as for feedback. 

## ♻️ Input & Output


<b>Type:</b> HDPE, LDPE, PP, PS<br>
<b>Output:</b> 1 part per 40 minutes. Depends largely on the mold.<br>


### How to operate the compression               

### Startup

1. Turn the oven on and set the desired temperature.
2. Wait 20 minutes for the desired temperature to be reached.

### Production

1. Weigh the required amount of material for your mold + 20%.
2. Fill the mold with material.
3. Put the upper part of the mold on the plastic.
4. Put the mold in the oven.
5. Leave it for 15 minutes.
6. Turn the mold 180° in the oven.
7. Leave it for another 15 minutes.
8. Compress the mold.
9. Take the mold out of the oven.
10. Put clamps on the mold to keep the pressure.
11. Place another mold in the oven.

### Cooldown
1. Clean the inside of the oven from molten plastic.
2. Tips & tricks while using
3. It is advisable to heat up the plastic until melted and then apply pressure.
4. Don’t be hasty, make sure the plastic is fully melted in the mold.


## Images of Compression Machine

<img src="https://i.imgur.com/Zwvsyj6.jpg" title="source: imgur.com" width ="350" height="300" align="left">

<img src="https://i.imgur.com/jIdz9qM.jpg" title="source: imgur.com" width ="350" height="300" align="right">

<img src="https://i.imgur.com/HKfs89y.jpg" title="source: imgur.com" width ="350" height="300" align="left">

<img src="https://i.imgur.com/rnWoTs3.jpg" title="source: imgur.com" width ="350" height="300" align="right">

<img src="https://i.imgur.com/aCIhP95.jpg" title="source: imgur.com" width ="350" height="300" align="right">

