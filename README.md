<img width="100%" alt="image" src="https://user-images.githubusercontent.com/38537119/159137387-00e4f052-0b33-4f50-91fa-72c485ebecb4.png">

__handy, micro power supply__ to drive your projects in all kind of situations! SquarePower fits in any toolbox and in any invention

* connects to an USB-C source, old laptop charger, ... (max 24V)
* outputs a fixed (1,8 V 2,5 V 3,3 V 5V 9V 12V), an adjustable voltage settings (0,8-17V) or simply redirects Vin to Vout
* up to a current 2,1A (max 3A - needs cooling)
* all these specs runs on two separate DCDC converters. Yes, you're right: It's dual output capable!

# 💊 Features 
__🛒 Easy to source__ : COTS-Principle for cost-efficient creating and repairing</br>
__♻️ Reuse__ : give a second life to your cables and chargers</br>
__🧩 Size__ : weights a few grams fits in +- 30x30x30cm space</br>
__💪🏽 Capable dual output__ : individual On/Off Switch, thermal and shortcircuit protection</br>
__🕶 Flexible__ : runs from a power bank, car battery, wall adaptor</br>
__🪛 DIY Friendly__ : design files & tutorials available</br>

More information about the DCDC Converter can be found [here](https://protosupplies.com/product/mp2315-mini-adjustable-dc-dc-step-down-module/)

# 🔦 Explanation

<p align="center">
<img width="780" alt="image"  src="https://user-images.githubusercontent.com/38537119/158996916-177053ac-f0dc-41ad-8121-35457cc2c5fa.png">
<img width="780" alt="image" src="https://user-images.githubusercontent.com/38537119/159089576-a0a85a92-84b2-4838-930e-5f01738d6f14.png">
</p>

## 🗺 Design Files

Designed in Eagle, in a messy way! Sorry! The related files are available under /Hardware.
Name | Description 
--- | ---
SQUAREPOWERV2 | VIN Vartions :</br>Jack, 3.5mm, horizontal, USB-C Trigger straight, below PCB
SQUAREPOWERVerticalUSBCV1 | VIN Vartions :</br> PCB USB-C right standing or straight, large pads for direct cable soldering

<p align ="center">
<img width="780" alt="image" src="https://user-images.githubusercontent.com/38537119/159140521-cc7cf26e-de17-417c-bf48-bd9c521bcd05.png">
</p>

You can order a prepared 10x10cm Panel version directly from DirtyPCB from here. You won't not only get a bunch a squarepower pcbs but also a few handy pcb for converting 3pin signals, voltage divider and power distributor.
<img width="120" alt="image" src="https://user-images.githubusercontent.com/38537119/159137529-948afa06-20f5-4229-a569-324e1078a4d4.png">


<p align="center">
  <img width="780" alt="image" src="https://user-images.githubusercontent.com/38537119/159152566-26dd1b0b-992d-407d-b471-d7321f70e51b.png">
</p>


## 🛠 For DIY'er:
All you need are steady hands for the soldering part. Small SMD (Surface Mount) components can be tricky to solder for beginners.

## 💰BOM
Part Name | Quantity | Price | Supply Link | Notes 
--- | --- | --- | --- | ---
PCB | 1x | 0,3€ | [DirtyPCB](https://dirtypcbs.com/store/designer/details/3748/6558/squarepower10x10panelv1-zip) or design files |Order your own or create the complete manufacturing process on your own 
Mini DCDC | 2x | 1€ | [Aliexpress](https://s.click.aliexpress.com/e/_9hSzDv) | should be based on IC [MP2315](https://www.openhacks.com/uploadsproductos/datasheet_77.pdf)

### Optional components

In case, you don't need any fancy control, feedback without the need 

Part Name | Quantity | Price | Supply Link | Notes 
--- | --- | --- | --- | ---
Screw Terminal 4 PIN | 3x | 0,40€ | [Aliexpress](https://s.click.aliexpress.com/e/_9jdwp1) | 2.54mm needs to be 4 pin - KF128
Mini Switch | 2x | 0,1€ | [Aliexpress](https://s.click.aliexpress.com/e/_A2f847) | Carefull, don't stress too much that component
LED | 2x | 0,10€ | [Aliexpress](https://s.click.aliexpress.com/e/_9vGqof) | 0805 Red, white, green... 
Resistors | 3x | 0,1€ | [Aliexpress](https://s.click.aliexpress.com/e/_A0ikLN) | 0805 - I would go for 1kΩ

### Variation : Removable or soldered DCDC converter 
Part Name | Quantity | Price | Supply Link | Notes 
--- | --- | --- | --- | ---
① Screw Terminal 4 PIN | 3x | 0,40€ | [Aliexpress](https://s.click.aliexpress.com/e/_AsaT637) | 2.54mm needs to be 4 pin
② Pin header | 3x | 0,40€ | [Aliexpress](https://s.click.aliexpress.com/e/_AsaT637) | 2.54mm needs to be 4 pin

### Variation : Vout Terminals
Part Name | Quantity | Price | Supply Link | Notes 
--- | --- | --- | --- | ---
① Plug Screw Terminal | 2x | 0,30€ | [Aliexpress](https://s.click.aliexpress.com/e/_A9i5w7) | 3.5mm needs to be 2 pin - can be straight or right angle **_OR_**            
② Screw Terminal | 2x | 0,30€ | [Aliexpress](https://s.click.aliexpress.com/e/_9GXJgJ) | 3.5mm needs to be 2 pin - KF350           

### Variation : Vin Terminals
Part Name | Quantity | Price | Supply Link | Notes 
--- | --- | --- | --- | ---
① Plug Screw Terminal | 2x | 0,30€ | [Aliexpress](https://s.click.aliexpress.com/e/_A9i5w7) | 3.5mm needs to be 2 pin - can be straight or right angle **_OR_**            
② USB-C Trigger | 1x | 1,30€ | [Aliexpress](https://s.click.aliexpress.com/e/_9GXJgJ) | best results with 20V Version **_OR_**       
③ Jack Barrel | 1x | 1,30€ | [Aliexpress](https://s.click.aliexpress.com/e/_9GXJgJ) | standard 2.1mm


🙏 Please if you need to shop for parts, it would be great that you use the supply links below. As they are affilated, you're supporting me directly to continue to deliver new projects to the community! Thank you!
At the moment I have no possibility for a larger production and distribution. Of course, I am ready for any cooperation to industrialize the production. 

## 👨🏼‍🏫Tutorials
Soon updates for:
* How to build your own & first steps
* Discover Ohm's Law with an USB Power Meter

## ✔ToDo
- [x] Redesign connections so the switches are symmetrical
- [ ] Add some space for soldering screw terminal right in place
- [ ] Add some tutorials about making and using!
- [ ] Design a nice laser-cutted and 3D printed enclosure
- [ ] Test if possible to arduino-drive the Enable Pin with a BSS138 Level Shifter
- [ ] Datasheet : Add 100k Resistor between Vin<--Switch-->Enable Pin
