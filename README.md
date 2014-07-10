SevenFortyFun
=============

SevenFortyFun, a transistor level op amp kit. [ <a href="http://openanalog.brace.io">OPEN ANALOG</a> ]

<b><a href="https://www.kickstarter.com/projects/1208645775/open-analog">KICKSTARTER CAMPAIGN!</a></b>

<img src="https://d2isyty7gbnm74.cloudfront.net/unsafe/276x276/square-production.s3.amazonaws.com/files/15bd0d0352ecbeb635dc87a63bf17537/original.jpeg">

<b>What's in this repo?</b>
  - Gerbers of SevenFortyFun Rev 1.0
  - Schematic (SevenFortyFun schematic.png)
  - LTSpice Simulation (SevenFortyFun Simulation.asc)
  - Tutorial/Guide of the SevenFortyFun, an explanantion of each transistors function (SevenFortyFun.pdf)

<b>To run LTSpice simulation download LTSpice (http://www.linear.com/designtools/software/) and then:</b>

  - View SevenFortyFun Simulation.asc
  - Click RAW
  - Copy to notepad (or your favorite text editor)
  - Save as .asc making sure 'save as type:' is selected to 'All Files'
  - Make sure encoding is ANSI
  - Open with LTSpice
  
or just download the whole thing as a zip...




<b>   INSTRUCTIONS FOR INSTALLING COMPONENTS: </b><br>
<b>   _______________________________________ </b>

<b> TRANSISTOR FOOTPRINT </b>
  - Collector denoted with silkscreen dot 

<b> PINOUT OF HEADERS </b>

  - 1:Non Inverting Input
  - 2:Inverting Input
  - 3:Offset Null 1
  - 4:Offset Null 2
  - 5:Output
  - 6:VCC
  - 7:-VCC
  - 8:GND

<b>TODO</b>
  - Make datasheet & characterize SevenFortyFun (i.e. slew rate, GBW, etc...)
  - Unify diagrams in the PDF/Make them look <i>pretty</i>
  - Edit out "ideal diode" comment in PDF with the more factual reality of a diode connected transistor - to obtain a very     low leakage diode. For example, a 3904 type transistor will have <1pA of reverse leakage using the Base Emitter     
    junction.
  
 
<br>
<br>
<br>

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
