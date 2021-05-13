# &#945;. Dré

__Or "How to fit a french ISO layout in a 40% keyboard ?"__


## Presentation

This project started as a need to find a new mechanical keyboard with a french ISO layout support. It also aims to keep a minimalistic design that we can find on most 40% keyboards. It will therefore include all the 3D CAD files and various pcb related files to conduct the project along with a documentation to build the keyboard.

### Renders

A bunch of renders have been made to validate the overall looking of the keyboard.

![alpha_dre_render1](dos/renders/alpha_dre_top_view4.png)

![alpha_dre_render2](doc/renders/alpha_dre_side_view4.png)

Complete set of renders can be found [here](dos/renders/renders_doc.md)

### Results

A first prototype with a simple skeleton case made out of plexiglass have been made to validate that the keyboard was responding correctly to the firmware and was usable. More on the cases will be done in the future (notably with the cut acrylic plates fot the sandwich mount).

<a data-flickr-embed="true" href="https://www.flickr.com/photos/192973713@N02/51174000281/in/album-72157719168472937/" title="IMG_7544"><img src="https://live.staticflickr.com/65535/51174000281_8f5fd61257_c.jpg" width="800" height="450" alt="IMG_7544"></a><script async src="//embedr.flickr.com/assets/client-code.js" charset="utf-8"></script>

<a data-flickr-embed="true" href="https://www.flickr.com/photos/192973713@N02/51175096930/in/album-72157719168472937/" title="IMG_7542"><img src="https://live.staticflickr.com/65535/51175096930_36d921167d_c.jpg" width="800" height="450" alt="IMG_7542"></a><script async src="//embedr.flickr.com/assets/client-code.js" charset="utf-8"></script>

### Layout

The keyboard presents 42 keys that are placed in an ISO layout, and even if the layout seems odd, most of keycaps set will fit this design. On the software side, the different layers of the keyboard remain to be done.

![alpha_dre_layout](docs/alpha_dre_layout.png)

### PCB

The pcb has been designed with Kicad software and gerbers files are available in the dedicated folder. This pcb hosts an Atmega32U4-AU for the keyboard control and is (as for other electronic components) soldered in surface. 

<a data-flickr-embed="true" href="https://www.flickr.com/photos/192973713@N02/51173328487/in/album-72157719168472937/" title="IMG_7497"><img src="https://live.staticflickr.com/65535/51173328487_4f60afffa1_c.jpg" width="800" height="450" alt="IMG_7497"></a><script async src="//embedr.flickr.com/assets/client-code.js" charset="utf-8"></script>

More on the pcb design available in the documentation file.

### Case

The case is a *high profile* one (meaning the eletronic parts and switches are hidden by the case) and has been designed to be manufactured with only laser cut acrylic plates of various sizes. These plates are fixed with M2 screws (M2x16) and are hidden with rubber bumps on the bottom of the case. This conception leads to a *sandwich mount* keyboard.

In order to give the keyboard a little angle for typing, two different feet have been design to be screwed at the back of the case.

A last option of low profile (barely no case) is available and needs practicaly no manufacturing. This option leads to a *tray mount* keyboard with no plate... 

![case_top_view](case/exploded_view_case.png)

### Parts

Here is a global list of all parts needed to perform this keyboard build:

- [ ] Laser cut acrylic plates
- [ ] Screws
- [ ] SMD components fot the pcb
- [ ] pcb plate
- [ ] 42 switches
- [ ] 6.25u and 2u stabilizers
- [ ] ISO keycap set
- [ ] Soldering tools
- [ ] Drill and threading tools


## Documents

- [case documentation](case/case_doc.md)
- [pcb documentation](pcb/pcb_doc.md)
- [firmware](firmware/alpha_dre/readme.md)


## Aknowledgment

- [Masterzen "Designing a keyboard from scratch" guide](https://www.masterzen.fr/2020/05/03/designing-a-keyboard-part-1/)
- [French mechanical keyboard community](https://github.com/mkbdfr) for their help and feedback