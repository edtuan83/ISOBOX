# ISOBOX
A ISO-enter mx based leverless controller

If you're anything like me, your addiction to keyboard has left you in an excess of several things - switches, unused keyset keys, and stabilizers (unless you collect 100% boards). I've never known what to do , considering for the most part I like 60 and 65% keyboards and have thus amassed a sizeable collection of spare parts. 

With the release of SF6, I was on the market for a leverless fightstick. I noticed that several commercial and community projects utilized keyboard switches mounted to a PCB for buttons. These boards would be mated with either Brooks or Rasberry Pi PCBs (yo dawg I heard you like PCBs) to allow them to function as game controllers, and have pretty simplistic routing and soldering when compared to keyboard PCBs. Seeing the overlap between these two hobbies of mine, the gears started spinning in my head, and the ISOBOX was born. 

The ISOBOX is a leverless fightstick based on jfedor2's Flatbox (https://github.com/jfedor2/flatbox). Specifically, this project utilizes the schematics from the Flatbox, but the pcb is redesigned and rerouted by me to instead utilize MX-style switches (instead of Kailh choc) and uses keyboard 2U stabilizers. Most notably, this board is set up to use ISO enters for all the buttons for strikes - great for a keyboard fiend like myself who ends up with a ton of spare parts. Since this project is based off the Flatbox rev5 schematic, it also utilizes the same pin-ins as the Flatbox, same RP2040-zero pcb, and consequently jfedor2's Flatbox rev5 firmware as well. I had also included some notches in hopes of eventually doing a gummy o-ring style mount for the pcb, but realized after ordering my first batch of PCBs that the use of on-board usb port from the RP2040-zero for connection will probably make this impossible with the current design. 

I've currently got black cherry pie switches installed in mine and it plays pretty well since the swithces have a really short travel distance for an MX switch. I've been using regular TX-stabilizers (I think rev2), and these are not perfect with the BCPs - they can definitely wobble and get stuck if you consciously press hard down on the corners, although this doesn't manifest itself during gameplay in my experience. I'm going to try some other stabilizers including the TX-longpoles to see how that goes.  

Intended next steps:
- Improve ergonomics: maybe angle the ISO enter array a little bit more to accommodate better posture (... an Alice ISOBOX???)
- Design a plate and stacked acrylic case to house this monstrosity.

Enjoy! Honestly this set up works surprisingly well! 
