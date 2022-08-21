 - 👋 Hi, I’m @HEN3DRIK
 - 👀 I’m interested in 3DPrinting and Electroforming/Electroplating
 - 📫 How to reach me 
   - Youtube https://www.youtube.com/c/v0g3l
   - Twitter https://twitter.com/v0g3l

# BeadSorter
Nice to have you here. In this repository I keep the files that are necessary for the BeadSorter. Also there will be documentation about the needed electronics and software. I will update this repo continuously.

# Video
[![perlerbead sorting machine](https://img.youtube.com/vi/CX-w85ZC5AQ/0.jpg)](https://www.youtube.com/watch?v=CX-w85ZC5AQ)

# References
These are Projects necessary for this beadsorter to work.

To simplify the printing process you can download these project in their respective folders in this repository.

Original Project by Linus Barth:
[BeadSort: Machine for sorting perler beads by LinusB - Thingiverse](https://www.thingiverse.com/thing:2598302) follow the process [here](STLs/LinusB/README.md).

Modified to skip aligner phase by RichA777
[Bead Sorter modified to skip aligner phase by RichA777 - Thingiverse](https://www.thingiverse.com/thing:4507571) follow the process [here](STLs/RichA777/README.md).

# Parts List
You'll need electronic parts for this bead sorter. This is alist of what i used in this project. I belive some components can be substituted.

- 1x Miniature-DC-Gear Motor 15RPM: https://www.amazon.de/gp/product/B08591W5N8/ref=ppx_yo_dt_b_asin_title_o08_s00?ie=UTF8&psc=1
- 2x LM2596S DC-DC: https://www.amazon.de/gp/product/B07YWLCTLK/ref=ppx_yo_dt_b_asin_title_o09_s00?ie=UTF8&psc=1
- 1x A4988 Stepper Driver Module: https://www.amazon.de/gp/product/B07C2V9GWC/ref=ppx_yo_dt_b_asin_title_o01_s00?ie=UTF8&psc=1
- 1x Nema 17 Stepper Bipolar 1A 16Ncm 42x20mm 4-Wires: https://www.amazon.de/dp/B06XVM38YW/ref=pe_27091401_487024491_TE_item
- 1x L298N Motor Drive Controller Board Module: https://www.amazon.de/gp/product/B07MY33PC9/ref=ppx_yo_dt_b_asin_title_o08_s01?ie=UTF8&psc=1
- 1x Adafruit-Sensor TCS34725 RGB: https://www.amazon.de/gp/product/B00OKCRU5M/ref=ppx_yo_dt_b_asin_title_o09_s01?ie=UTF8&psc=1
- 1x Arduino Nano V3.0 Atmega328 CH340: https://www.amazon.de/gp/product/B01MS7DUEM/ref=ppx_yo_dt_b_asin_title_o03_s00?ie=UTF8&psc=1
- 1x SG90 Micro Servo Motor 9G: https://www.amazon.de/gp/product/B07CYZSVKW/ref=ppx_yo_dt_b_asin_title_o03_s00?ie=UTF8&psc=1
- 1x 100µF Capacitor
- 1x Resistor matching LED
- 1x White LED
- 1x Photo Resistor 5mm
- 1x Push Button
- Wires
- PTFE Spray

# Electronics Schema
I know, this isn't nice looking.
![alt text](https://github.com/HEN3DRIK/BeadSorter/blob/main/beadsorter_schema.png?raw=true)

# Printing Guide
Once you copied the STL files from the reference project into their respective directory launch the script ExtractParts.bat (double click on it).
The table below refers to parts in to TO_PRINT folder.

Part | Quantity
--- | ---
0-hopper-seq-plate-4_holes_modified.stl              | 1
0-hopper-seq-stopper.stl                             | 1
1-sequentializer-ilc-bottom.stl                      | 1
1-sequentializer-ilc-corner_for_higher_motor.stl     | 4
1-sequentializer-ilc-top.stl                         | 1
1-sequentializer-motor-holder.stl                    | 1
3-analyzer-base.stl                                  | 1
3-analyzer-entry-tube_modified.stl                   | 1
3-analyzer-exit-base.stl                             | 1
3-analyzer-exit-tube.stl                             | 1
3-analyzer-ilc-bottom.stl                            | 1
3-analyzer-ilc-corner.stl                            | 4
3-analyzer-ilc-top.stl                               | 1
3-analyzer-separation-arm.stl                        | 1
3-analyzer-servo-holder.stl                          | 1
3-analyzer-top-alignment.stl                         | 1
4_Stepper_shaft.stl                                  | 1
4-dispatcher-ilc-bottom.stl                          | 1
4-dispatcher-ilc-corner.stl                          | 4
4-dispatcher-ilc-top.stl                             | 1
4-dispatcher-tube-alignment.stl                      | 1
4-dispatcher-tubehalf-1.stl                          | 1
4-dispatcher-tubehalf-2.stl                          | 1
5-outputs-ilc-corner.stl                             | 4
5-outputs-ilc-top.stl                                | 1
5-outputs-slide-1.stl                                | 4
5-outputs-slide-2.stl                                | 4
5-outputs-slide-3.stl                                | 4
Box_bottom.stl                                       | 1
Box_lid.stl                                          | 1
Box_top.stl                                          | 1
holder_typeA.stl                                     | 1
holder_Typeb.stl                                     | 1
Hopper_Modified_Cleaned_up.stl                       | 1
Plate.stl                                            | 1
ring_container.stl                                   | 1
Sequencer_base_modified.stl                          | 1
Servo_base2.stl                                      | 1
Stepper_shaft_ring.stl                               | 1
UM2_Sequencer_tube_modified_tighter_Higher_Motor.stl | 1
TOTAL                                                | 61