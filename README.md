# Synth From Scratch

## Money Shot

![Final Product](https://raw.githubusercontent.com/DragosRotaru/Synth-From-Scratch/master/Final2-compressor.jpg)


## Introduction

Synthesizers are hypnotic. The beeps and boops they produce induce an almost involuntary urge to move – they enact on our primal need to respond to the call of rhythm and groove. For years I dreamt of the day that I would be able to twist knobs, push buttons and slam down some analog basslines. 

Anyway the point is I built an analog modular synthesizer. Its not really done, I left a lot of space for future additions with the intent to add a module to it every so often – it is complete in the sense that I have finished the first batch of 12 modules.  In my senior year of high school I decided to challenge myself by building something truly *difficult*. I decided to pick a project described on the documentation page as follows: 

>This is an advanced project requiring understanding of electronics and electronic building and trouble shooting skills and equipment. Access to a good oscilloscope, DVM, bench power supply, soldering station and hand tools will be required. Only the schematic, circuit description, and suggested panel layout are provided. Please read over the entire project and make sure the information is clear enough for you to succeed before ordering PC boards or other products.

Without further ado, here is the story of how I spent 2 years overcoming the many obstacles one faces when they decide to build an advanced electronics project with no previous experience and a lack of tools. 

## Design 

The design of this project is largely consistent with the original designed by Ray Wilson. You can find that project [here](http://musicfromouterspace.com/index.php?MAINTAB=SYNTHDIY&VPW=1670&VPH=802). I originally attempted to produce a PCB based on files provided with the project. Unfortunately after 4 attempts at photolithographic PCB etching with a garbage setup I decided to build the whole thing in modules on some decent perf-board. I wish I took photos of the etched boards, they were a mess. The method works very well for small boards, and can produce quality boards if you have the money for a decent lazer printer and exposure / etching setup. I have since decided that I will never, **ever** build a large project on perfboard. I will instead use a pcb prototyping service like OSH Park. I will also never, **ever** waste time doing photolithographic etching.

Many alterations to the original design were made to convert the synth to a modular system. This includes replacing switch based connections with jacks and creating completely new panel designs. You can see that below:

![Block Assembly Diagram](https://raw.githubusercontent.com/DragosRotaru/Synth-From-Scratch/master/BlockAssembly.jpg)

I also designed the analog power-supply and power distribution system for the project. I dont have pictures or schematics of that but it is very straight forward – a fully rectified and heavily filtered AC to DC linear supply that provides +/-12V. This feeds to a 12v to 5v  SMPS module and to the power bus.

The case is fully compliant with the EuroRack standard – You can read about that [here](http://www.doepfer.de/a100_man/a100m_e.htm). The case is built using plywood, aluminum L-bar and rivets. I installed EuroRack slide-nut rails purchased from [SynthroTek](http://store.synthrotek.com/Eurorack_Vector_Rails). The case also has large aluminum feet I salvaged from an old amplifier. 


## The Build

As mentioned before, this project was a pain in the ass. I started with almost zero knowledge pertaining to analog electronics design and analysis. I didn't even own a power supply, oscilloscope or decent soldering iron. All I had was around $1000, experience with digital electronics and some tools laying around the basement. Unfortunately, that isn't even the bad part. The bad part is the fact that for months on end I either had no access to necessary (ie no drill press), or access to poor tools that weren't ideal (i.e. wood drillbits when I needed aluminum bits). Here are some of the lessons I have learned:

* Do NOT use perfboard for complex projects.
* Do NOT use photolithographic etching for complex projects.
* Do use a PCB prototyping service.
* Do NOT waste money at expensive local distributors.
* Do waste money at DigiKey, Mouser or any other respectable distributor.
* Do NOT use inappropriate gauge/type of wire.
* Do NOT start a complex project if you dont have or know where to get all the tools to finish.
* Do NOT use a paint pen ever, for any reason whatsoever. They suck.
* Do always double check and triple check your soldering job.
* Do NOT use shitty drill presses or drill bits.
* Do NOT try to do DIY transistor matching. You can buy Vbe matched transistor pairs in SMT packages.
* Do spend money on decent tools
* Do NOT attend a garbage university with no access to workshops for computer science students.
* Do own a car so that you dont have to bus for 10 minutes to your local hackerspace hauling boxes of stuff.



<img src="https://raw.githubusercontent.com/DragosRotaru/Synth-From-Scratch/master/Final1-compressor.jpg" width="256">
<img src="https://raw.githubusercontent.com/DragosRotaru/Synth-From-Scratch/master/Final3-compressor.jpg" width="256">
<img src="https://raw.githubusercontent.com/DragosRotaru/Synth-From-Scratch/master/Final4-compressor.jpg" width="256">
<img src="https://raw.githubusercontent.com/DragosRotaru/Synth-From-Scratch/master/FInal5-compressor.jpg" width="256">
<img src="https://raw.githubusercontent.com/DragosRotaru/Synth-From-Scratch/master/WorkshopMess-compressor.jpg" width="256">
<img src="https://raw.githubusercontent.com/DragosRotaru/Synth-From-Scratch/master/CircuitsOnTable-compressor.jpg" width="256">
<img src="https://raw.githubusercontent.com/DragosRotaru/Synth-From-Scratch/master/CircuitOnTable-compressor.jpg" width="256">
<img src="https://raw.githubusercontent.com/DragosRotaru/Synth-From-Scratch/master/DrillingPanels-compressor.jpg" width="256">
<img src="https://raw.githubusercontent.com/DragosRotaru/Synth-From-Scratch/master/DeburredPanel-compressor.jpg" width="256">
<img src="https://raw.githubusercontent.com/DragosRotaru/Synth-From-Scratch/master/PaintedPanels-compressor.jpg" width="256">
<img src="https://raw.githubusercontent.com/DragosRotaru/Synth-From-Scratch/master/WritingOnPanels-compressor.jpg" width="256">
<img src="https://raw.githubusercontent.com/DragosRotaru/Synth-From-Scratch/master/MountingJacks-compressor.jpg" width="256">
<img src="https://raw.githubusercontent.com/DragosRotaru/Synth-From-Scratch/master/AssembledADEnv-compressor.jpg" width="256">
<img src="https://raw.githubusercontent.com/DragosRotaru/Synth-From-Scratch/master/AssembledADEnvFront-compressor.jpg" width="256">
<img src="https://raw.githubusercontent.com/DragosRotaru/Synth-From-Scratch/master/MountingModules-compressor.jpg" width="256">
<img src="https://raw.githubusercontent.com/DragosRotaru/Synth-From-Scratch/master/Tuning-compressor.jpg" width="256">


