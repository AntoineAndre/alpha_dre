# &#945;. Dré

__Or "How to fit a french ISO layout in a 40% keyboard ?"__


## Presentation

This project started as a need to find a **new mechanical keyboard with a french ISO layout support**. It also aims to keep a minimalistic design that we can find on most 40% keyboards. It will therefore include all the 3D CAD files and various pcb related files to conduct the project along with a documentation to build the keyboard.

### Renders

A bunch of renders have been made to validate the overall looking of the keyboard.

![alpha_dre_render1](docs/renders/alpha_dre_top_view4.png)

![alpha_dre_render2](docs/renders/alpha_dre_side_view4.png)

__Complete set of renders__ can be found __[here](dos/renders/renders_doc.md)__

### Results

A first prototype with a simple skeleton case made out of plexiglass have been made to validate that the keyboard was responding correctly to the firmware and was usable. More on the cases will be done in the future (notably with the cut acrylic plates for the sandwich mount and with a 3d printed case).

![pic_front](https://live.staticflickr.com/65535/51174000281_2e8926cdd9_h.jpg)

![pic_side](https://live.staticflickr.com/65535/51175096930_bc8a597342_h.jpg)

**The complete album containing all the pictures** made on the prototype is available **[here](https://flic.kr/s/aHsmVCqc8F)**

### Layout

The keyboard presents 42 keys that are placed in an ISO layout, and even if the layout seems odd, most of keycaps set will fit this design. With juste 3 layers the keyboard becomes fully usable as shown in the firmware part.

![alpha_dre_layout](docs/alpha_dre_layout.png)

### PCB

The pcb has been designed with Kicad software and gerbers files are available in the dedicated folder. This pcb hosts an Atmega32U4-AU for the keyboard control and is (as for other electronic components) soldered in surface. 

![pic_pcb](https://live.staticflickr.com/65535/51173328487_bfa592c227_h.jpg)

More on the pcb design available in the documentation file.

### Case

The case is a *high profile* one (meaning the eletronic parts and switches are hidden by the case) and has been designed to be manufactured with only laser cut acrylic plates of various sizes. These plates are fixed with M2 screws (M2x16) and are hidden with rubber bumps on the bottom of the case. This conception leads to a *sandwich mount* keyboard.

In order to give the keyboard a little angle for typing, two different feet have been design to be screwed at the back of the case.

A last option of low profile (barely no case) is available and needs practicaly no manufacturing. This option leads to a *tray mount* keyboard with no plate (this is the chosen option shown in the begining of this presentation).

![case_top_view](case/exploded_view_case.png)

### Parts

Here is a global list of all parts needed to perform this keyboard build:

- [ ] Laser cut acrylic plates
- [ ] Screws (M2 for sandwich mount and M3 for skeleton mount)
- [ ] SMD components fot the pcb (see the pcb documentation for more details)
- [ ] pcb plate
- [ ] 42 switches
- [ ] 6.25u and 2u stabilizers
- [ ] ISO keycap set
- [ ] Soldering tools
- [ ] Drill and threading tools


## Documents

- [case documentation](case/case_doc.md)
- [pcb documentation](pcb/pcb_doc.md)
- [firmware documentation](firmware/alpha_dre/readme.md)


## Aknowledgment

- [Masterzen "Designing a keyboard from scratch" guide](https://www.masterzen.fr/2020/05/03/designing-a-keyboard-part-1/)
- [French mechanical keyboard community](https://github.com/mkbdfr) for their help and feedback
