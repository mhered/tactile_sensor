# README.md

Adding tactile sensors to my robots

Planning to use eFlesh: [Website: e-flesh.com](https://e-flesh.com/) | [Github repo](https://github.com/notvenky/eFlesh)

Which in turn seems inspired by [Reskin](https://reskin.dev/)

I am planning to instrument the [PincOpen gripper](https://pollen-robotics.github.io/PincOpen/) and install it on the [SO100ARM robotic arm](https://github.com/TheRobotStudio/SO-ARM100).

My intention is to open source the result. There is a very active growing community around the [lerobot project](https://github.com/huggingface/lerobot) sharing AI robotics training data. Today training is mainly using video, but making a low-cost tactile sensor available would allow using also touch inputs, which would open up many great possibilities

## BOM

* 3D Printing Filament 1.75mm TPU 95A (Flexible, Transparent Blue color) from [Amazon](https://www.amazon.es/dp/B07WGK7J48): 12.13€

* A pack of 220 ZENYKX 3x1mm N52 magnets from [Amazon](https://www.amazon.es/dp/B0DDH9M2YY): 8.99€ > may be too small

* A pack of 120 Wzone 5x2mm magnets from [Amazon](https://www.amazon.es/dp/B0CPT2S1XR): 9.99€  > not clear these are N52

* A pack of 50 Aprilheld 5x2mm N52 magnets from [Amazon](https://www.amazon.es/dp/B0D3YQ5KH3): 16.99€ 

* Purchased a PCB (60$ including shipping)  but can also be sent to manufacture, see: https://github.com/raunaqbhirangi/reskin_sensor/tree/main/circuits

## 3D printing

Filament specs & manufacturer print settings:

* Filament diameter: 1.75 mm

* Dimensional accuracy: +/- 0.05 mm

* Extruder temperature: 190°C - 220°C

* Bed temperature: 40°C - 60°C

* Print speed: 10 - 30 mm/s
