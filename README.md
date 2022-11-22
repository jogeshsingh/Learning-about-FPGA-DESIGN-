# Learning-about-FPGA-DESIGN
This repository contains some introductory level course review about learning about FPGA Design including some tutorials, links to websites and some blogs related to learning about FPGA RTL Design. 

# Introduction
 What is an FPGA?
 
 FPGA - in short , is called as FIELD PRORGRAMMABLE GATE ARRAYS . It is a sort of reconfigurable piece of hardware which can be programmed for any number of times , allowing user to change its functionality depending upon what the user wants it to behave like . It consists of large number of configurable logic blocks (including LUTs(Look up tables)  , Flip flops , Multiplexer ) , Programmable logic interconnect(responsible for intrconnecting different modules inside the FPGA FABRIC) , and I/O blocks(for communicating with peripherals). 
 
 What do i need to learn about FPGAs?
 
  To learn about FPGAs isn't a big deal . It is starts with basic building blocks of how computer operates in binary . Yeah ? You got it right . It is just a binary (   Zero's(0) and one's(1)) . Remember!!! You're defining a digital circuit in FPGA , so needn't worry about analogue signal traces like the one we used to in 
  analog  design , however in the end everything is analog by nature !!!.
  
       Learning about FPGA is pretty steep learning curve , so don't be disappointed if your design run into erros multiple times.
      
 
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
 
 Let's go some years back , when engineers used to define circuits using schematic design editor , which got cumbersome with the time when they found their design got bigger as the moore's law proceeded ,limiting the designer's perspective on interconnecting large buidling block through hundered of thousands of wires coming up inside a single microprocessor. for someone wanted to gauge their Digital ciruits skills in depth- : 
 https://ocw.mit.edu/courses/6-004-computation-structures-spring-2009/pages/lecture-notes/
 
 Then in 1985 , Gateway design automation released a language called VERILOG HDL , A hardware  description language , allowing designers to build logic circuits in EDA Software , thus reducing their time to minimal as designers now could look at the schematic generated through HDL code they written through the RTL(Register tranfer level) viewer.
 
  Note -: For installing vivado , make sure you have enough internet data available at your end ..
  
 # REQUIREMENTS FOR SETTING UP THE FPGA DESIGN ENVIRONMENT
    laptop , pc : windows 10 (for WIN 11 , you may have to setup in virtual box) or linux or Mac.
    Software    : Xilinx VIVADO (any version after 2015 is fine, pretty easy to use with inbuilt simulation envrionment) .
    Storage     : Depends on which version of VIVADO is being installed .
    Toolchain   : There are many fpga boards available in the market , some are quite costly , but it is upto you which one to choose . 
    
 
 # FPGA 01 
   Here I am posting some introductory links for gearing yourself up ahead --:
   1. https://fpgatutorial.com/
   2. http://www.asic-world.com/verilog/veritut.html ( for verilog refresh)
   3. https://www.sparkfun.com/fpga
   4. https://hardwarebee.com/fpga-design/
   5. https://www.electronicdesign.com/technologies/fpgas/article/21801527/the-principles-of-fpgas
   6. https://codilime.com/blog/fpga-programming-how-it-works-and-where-it-can-be-used/
   7. https://www.intel.com/content/dam/support/us/en/programmable/support-resources/bulk-container/pdfs/literature/misc/fpgas-for-dummies-ebook.pdf
   
   
   Reminder !!! in HDL , you're describing a piece of hardware logic not a software , so don't consider HDL as just programming language.
   
 # VERILOG 01 
  Here are some of the resources for learning about VERILGO HDL 
  1. https://www.chipverify.com/verilog/verilog-tutorial
  2. https://acg.cis.upenn.edu/milom/cis371-Spring13/lab/textbook-verilog-tutorial/VOL/main.htm ( This one would surely help you master the concepts of verilog HDL)
  3. https://verilogguide.readthedocs.io/_/downloads/en/latest/pdf/ 
    ( This one is quite underrated for beginners , you can jump directly to overview(chapter 02 , 
     staring the verilog section) , as in chapter 01 , author uses the schematic entry so needn't go through it , if you're planning to learn using HDL, but its worth      looking at how schematic capture tool works too ).
  3. https://people.ece.cornell.edu/land/courses/ece5760/Verilog/Verilog_index.html
  4. http://www.sunburst-design.com/papers/   ( For learning about Verilog , System verilog design methodologies , UVM and many more advanced concepts ).
  5. 
   
   # FPGA (online courses links & University lab access material)
  1. https://people.ece.cornell.edu/land/courses/ece5760/
  2. https://www.coursera.org/specializations/fpga-design ( You can also apply for financial aid ).
  3. https://www.coursera.org/learn/fpga-intro
  

   # FPGA (e-books)
   1.https://www.fpgakey.com/
   
   # FPGA (Verilog HDL coding examples)
   1. https://fpgacoding.com/
   
   # FPGA Reddit page 
   1.https://www.reddit.com/r/FPGA/
   
   2.https://www.reddit.com/r/Verilog/
   
   3.https://www.reddit.com/r/cpudesign/
   
   # The only person I have seen demonstrating FPGA Design in Depth ...
   
   Thanks to https://github.com/ZipCPU
  
   Take a look at his website..
  
   https://zipcpu.com/
   
  # Miscellaneous 
   1. https://chiphackers.com/lessons/ 
 
  
  # Open source tool for practicing HDL 
   1. https://www.edaplayground.com/home  ( you can login using your google account , but using that you'll have access to only few tools , others require industrial          verified account ) .
   2. https://hdlbits.01xz.net/wiki/Main_Page     ( this one is pretty good site , making your fundamentals strong is the one way out from here ).
   3. https://chipdev.io/                     ( This one is a bit advanced , required some previous experience in writing HDL code) .
   4.
   
  
   # FPGA TOOLS
    
   
   1. Xilinx(AMD) VIVADO ( webpack edition is free to be installed).
      https://www.xilinx.com/support/download/index.html/content/xilinx/en/downloadNav/vivado-design-tools/archive.html
      
      For windows 10 -:   https://www.xilinx.com/member/forms/download/xef.html?filename=Xilinx_Unified_2020.3_0407_2214_Win64.exe
      for Linux      -:   https://www.xilinx.com/member/forms/download/xef.html?filename=Xilinx_Unified_2020.3_0407_2214_Lin64.bin
      
      How to install Xilinx VIVADO ?
      watch this video -:
      https://youtu.be/yW7t28XaVEs
     
      installed the vivado ?
      Then watch this video to know,  how to get started with ---:
       https://youtu.be/BBtD4PCXqlE
      
   2. Quartus prime lite Edition + Modelsim simulator( from Intel , is free to be installed)
      How to install Quartus prime lite edition tool ?
      watch this video  -:)
      https://youtu.be/HO7yOu0C6bA
      
      How to get started building the logic and simulating the design in Quartus + Modelsim ?
      watch this video -:)
      https://youtu.be/YSQnVqXt3do
      
      
      
   
      
 
 
 

