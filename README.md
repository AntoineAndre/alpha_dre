# Alpha Dré

__Or "How to fit a french ISO layout in a 40% keyboard ?__

Small 42-key mechanical keyboard with ISO layout (french)

This project aims to create a minimalist mechanical keyboard from scratch. It will therefore include all the 3D files and various pcb related files.

## Renders

As this keyboard is in a "pre-project" state, some renders have been made to evaluate the feasability and the arrangement of the keys.

![alpha_dre_render1](renders/alpha_dre_render1.png)

![alpha_dre_render2](renders/alpha_dre_render2.png)

## Layout

The physical layout of the keyboard presents 42 keys that are compatible with most of keycaps sets.

![alpha_dre_layout](docs/alpha_dre_layout.png)

The different layers of the keyboard still remain unknown at the moment...

## PCB

The PCB requires SMD components, the list of all electronic parts is presented below:

|Id |Designator  |Package                                       |Quantity |Designation       |
|---|------------|----------------------------------------------|---------|------------------|
|3  |MX switches |SW_Cherry_MX PCB mount                        |42       |MX-NoLED          |
|9  |FB1         |L_0805_2012Metric_Pad1.15x1.40mm_HandSolder   |1        |Ferrite_Bead_Small|
|10 |USB1        |HRO-TYPE-C-31-M-12-HandSoldering              |1        |HRO-TYPE-C-31-M-12|
|11 |U2          |SOT143B                                       |1        |PRTR5V0U2X        |
|12 |SW1         |SW_SPST_SKQG_WithStem                         |1        |SW_Push           |
|13 |R6,R5       |R_0805_2012Metric_Pad1.20x1.40mm_HandSolder   |2        |5.1k              |
|14 |R4,R3       |R_0805_2012Metric_Pad1.20x1.40mm_HandSolder   |2        |10k               |
|15 |R2,R1       |R_0805_2012Metric_Pad1.20x1.40mm_HandSolder   |2        |22                |
|16 |J1          |Reset_Pretty-Mask                             |1        |AVR-ISP-6         |
|17 |C8,C3,C2,C1 |C_0805_2012Metric_Pad1.18x1.45mm_HandSolder   |4        |0.1uF             |
|18 |Y1          |Crystal_SMD_3225-4Pin_3.2x2.5mm_HandSoldering |1        |16MHz             |
|19 |U1          |TQFP-44_10x10mm_P0.8mm                        |1        |ATmega32U4-AU     |
|20 |F1          |Fuse_1206_3216Metric_Pad1.42x1.75mm_HandSolder|1        |500mA             |
|21 |C7          |C_0805_2012Metric_Pad1.18x1.45mm_HandSolder   |1        |1uF               |
|22 |C6          |C_0805_2012Metric_Pad1.18x1.45mm_HandSolder   |1        |10uF              |
|23 |C5,C4       |C_0805_2012Metric_Pad1.18x1.45mm_HandSolder   |2        |22pF              |
|24 |D           |D_SOD-123                                     |42       |D_Small           |

The 3D view of the PCB looks like this:

![pcb_front](docs/alpha_dre_pcb_top.png)

![pcb_back](docs/alpha_dre_pcb_bottom.png)