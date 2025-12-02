# Elliott's HackPad!!
My first project through hackclub!!! I kinda feel like I missed out on a lot by learning about hackclub so late in highschool :(( but I'm coping by doing this (also hi Sam:3 ) I'm mostly doing this for learn a bit about python, kicad, and making pcbs. Probably just gonna use it for macros and such but I do wanna add some lights that react to keys being pushed because I think it's cool :3

## Features
- 4 Switches, each with an assigned macro
- 4 LEDs 
- Volume knob
- A monochrome .091" OLED display for animations

## CAD 
Made with a combo of Fusion and Onshape! (dont ask...)

![meow](https://hc-cdn.hel1.your-objectstorage.com/s/v3/270cdb58b806dd5ffc7fc664e083cb5672925a07_image.png)

You'll need to make a I2C wire to plug the OLED into the pin header on the PCB

## PCB

| **Schematic** | **PCB** |
|---------------|---------|
|![](https://hc-cdn.hel1.your-objectstorage.com/s/v3/24ea2686bdf736fe201b03aaaa7aa43ab714c879_image.png)|![](https://hc-cdn.hel1.your-objectstorage.com/s/v3/6b7201e25fb772890c47c8185c7b606820831a0e_image.png)|

![meow2](https://hc-cdn.hel1.your-objectstorage.com/s/v3/2c76e545b5820225a5230012eaa27399d28c0e67_image.png)

Had to redo the routing like 5 times but it should all be good now X3

## Firmware 

Still a work in progress!!! Im using kmk to write it, but I have a lot to learn first tho....\
<sub>I've never used python before:3</sub>

## BOM
- 1x Case (From CAD file)
- 1x Seeed XIAO RP2040 
- 1x 0.91 inch OLED 
- 1x EC11 Rotary Encoder
- 4x Cherry MX Switches
- 4x DSA Keycaps
- 4x SK6812 MINI-E LEDs
- 4x M3x16mm screws
- 4x M3x5mx4mm heatset inserts 
