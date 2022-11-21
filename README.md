# Learning-about-FPGA-DESIGN
This repository contains some introductory level course review about learning about FPGA Design including some tutorials, links to websites and some blogs related to learning about FPGA and RTL Design. 

# Introduction
 What is an FPGA?
 
 FPGA - in short , is called as FIELD PRORGRAMMABLE GATE ARRAYS . It is a sort of reconfigurable piece of hardware which can be programmed for any number of times , allowing user to change its functionality depending upon what the user wants it to behave like . It consists of large number of configurable logic blocks (including LUTs(Look up tables)  , Flip flops , Multiplexer ) , Programmable logic interconnect(responsible for intrconnecting different modules inside the FPGA FABRIC) , and I/O blocks(for communicating with peripherals). 
 
 What do i need to learn about FPGAs?
 
  To learn about FPGAs isn't a big deal . It is starts with basic building blocks of how computer operates in binary . Yeah ? You got it right . It is just a binary (   Zero's(0) and one's(1)) . Remember!!! You're defining a digital circuit in FPGA , so needn't worry about analogue signal traces like the one we used to in 
  analog  design , however in the end everything is analog by nature !!!.
 
 One should be knowing how logic gates work.
 (Those who are already familiar with them , just skip to FPGA part 1).
        
  wanna learn about them ---: click on here...-->>
  1 .https://www.elprocus.com/basic-logic-gates-with-truth-tables/

  wanna learn how to design using tool --->>
    1 .https://en.freedownloadmanager.org/users-choice/Download_Proteus_For_Windows_10.html
    2. https://sourceforge.net/projects/circuit/
    3. https://circuitverse.org/
 
 I know , Many of us are familiar with those . but how do those things actually implemented in physical hardware. Now this stuff gets down to CMOS (Complementary Metal Oxide Semiconductor ) , that's another part of story , beacuse in FPGA we don't need to define and build the CMOS from scratch , like in ASIC there it is necessary in some cases while developing standard cell librray in EDA tools. But in FPGA , we just need to know Logic gates and their functionality . 
 
 Remember this is the beginning while learning about FPGA....
 
 How do i design the logic gates in FPGA , or in other words how to define the behaviour of basic digital logic module in FPGA ?
 
 Let's go some years back , when engineers used to define circuits using schematic design editor , which got cumbersome with the time when they found their design got bigger as the moore's law proceeded ,limiting the designer's perspective on interconnecting large buidling block through hundered of thousands of wires coming up inside a single microprocessor. for someone wanted to gauge heir Digital ciruits learning in depth- : 
 https://ocw.mit.edu/courses/6-004-computation-structures-spring-2009/pages/lecture-notes/
 
 Then in 1985 , Gateway design automation released a language called VERILOG HDL , A hardware  description language , allowing designers to build logic circuits in EDA Software , thus reducing their time to minimal as designers now could look at the schematic generated through HDL code they written through the RTL(Register tranfer level) viewer.
 
 
 # REQUIREMENTS FOR SETTING UP THE FPGA DESIGN ENVIRONMENT
    laptop , pc : windows 10 (for WIN 11 , you may have to setup in virtual box) or linux or Mac.
    Software    : Xilinx VIVADO (any version after 2015 is fine, pretty easy to use with inbuilt simulation envrionment) .
    
    
 
 # FPGA 01 
   Here I am posting some introductory links for gearing yourself up ahead --:
   1. https://fpgatutorial.com/
   2. http://www.asic-world.com/verilog/veritut.html ( for verilog refresh)
   3. https://www.sparkfun.com/fpga
   4. https://hardwarebee.com/fpga-design/
   5. https://www.electronicdesign.com/technologies/fpgas/article/21801527/the-principles-of-fpgas
   
 # VERILOG
   
 
 
 

