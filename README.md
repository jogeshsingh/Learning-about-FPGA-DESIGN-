 # Learning-about-FPGA-DESIGN
This repository contains some introductory level course review for learning about FPGA Design including some tutorials, links to some websites and some blogs related to FPGA RTL Design. 

# Introduction
 What is an `FPGA` ?
 
 ![OIP](https://user-images.githubusercontent.com/98607828/203379311-a418acb2-a16e-4ce6-9300-4d970efa5113.jpg)

 - `FPGA` - in short , is called as `FIELD PRORGRAMMABLE GATE ARRAYS` . It is a sort of reconfigurable piece of hardware which can be programmed for any number of times , allowing user to change its functionality depending upon what the user wants it to behave like . It consists of large number of configurable logic blocks (including LUTs(Look up tables)  , Flip flops , Multiplexer ) , `Programmable logic interconnect`(responsible for interconnecting different modules inside of an FPGA FABRIC) , and I/O blocks(for communicating with peripherals).

 - `What are Look-up Tables inside of an FPGA Architecture ?` [Check_here](https://hardwarebee.com/overview-of-lookup-tables-in-fpga-design/)

  **`WHAT DO YOU NEED TO LEARN ABOUT FPGAs?`**
 
-  Learning about FPGAs isn't a big deal . It is starts with basic building blocks of how computer operates in binary . `Yeah` ?
-  You got it right . It is just a binary (   Zero's(`0`) and one's(`1`)) .
-  Remember!!! You're defining a digital circuit in FPGA , so needn't worry about `analoge signal` traces like the one we used to in analog  design ,
- `however` in the end everything is `analog` by nature !!!.

- Learning about FPGA is pretty steep learning curve , so don't be disappointed if your design run into erros multiple times.

  [FPGA_HISTORY_AND_APPLICATIONS](https://queue.acm.org/detail.cfm?id=3411759)
      
 
- One should be knowing how logic gates work.
 (Those who are already familiar with them , just skip to `FPGA 01`) .
        
-  wanna learn about them ---: [click_on_here](https://www.elprocus.com/basic-logic-gates-with-truth-tables/)

 - wanna learn how to design using tool 

    [PROTEUS](https://en.freedownloadmanager.org/users-choice/Download_Proteus_For_Windows_10.html)

      https://sourceforge.net/projects/circuit/

    [CIRCUIT_VERSE](https://circuitverse.org/)
 
 I know , Many of us are familiar with those . but how do those things actually get implemented in physical hardware. Now this stuff gets down to CMOS (Complementary Metal Oxide Semiconductor ) , that's another part of story , beacuse in FPGA we don't need to define and build the CMOS from scratch , like in ASIC there it is necessary in some cases while developing standard cell librray in EDA tools. But in FPGA , we just need to know Logic gates and their functionality . 
 
 `Remember!` this is the beginning while learning about FPGA....
 
 How do i design the logic gates in FPGA , or in other words how to define the behaviour of basic digital logic module in FPGA ?
 
- Let's go some years back , when engineers used to define circuits using schematic design editor , which got cumbersome with the time when they found their design got bigger as the moore's law proceeded ,limiting the designer's perspective on interconnecting large buidling block through hundered of thousands of wires coming up inside a single microprocessor. for someone wanted to gauge their Digital ciruits skills in depth- : 
 https://ocw.mit.edu/courses/6-004-computation-structures-spring-2009/pages/lecture-notes/
 
- Then in 1985 , Gateway design automation released a language called VERILOG HDL , A hardware  description language , allowing designers to build logic circuits in EDA Software , thus reducing their time to minimal as designers now could look at the schematic generated through HDL code they written through the RTL(Register tranfer level) viewer.
 
  Note -: For installing vivado , make sure you have enough internet data available at your end ..
  
 # REQUIREMENTS FOR SETTING UP THE FPGA DESIGN ENVIRONMENT
    laptop , pc : windows 10 (for WIN 11 , you may have to setup in virtual box) or linux or Mac.
    Software    : Xilinx VIVADO (any version after 2015 is fine, pretty easy to use with inbuilt simulation envrionment) .
    Storage     : Depends on which version of VIVADO is being installed .
    Toolchain   : There are many fpga boards available in the market , some are quite costly , but it is upto you which one to choose . 
    
 
 # FPGA 01 
   Here I am posting some introductory links for gearing yourself up ahead --:
   1. [FPGA Tutorial](https://fpgatutorial.com/)
   2. [ASIC_WORLD](http://www.asic-world.com/verilog/veritut.html) ( for verilog refresh)
   3. [SPARKFUN_FPGA](https://www.sparkfun.com/fpga)
   4. [HARDWARE_BEE](https://hardwarebee.com/fpga-design/)
   5. [PRINCIPLES_OF_FPGA](https://www.electronicdesign.com/technologies/fpgas/article/21801527/the-principles-of-fpgas)
   6. [CODELIME_BLOG](https://codilime.com/blog/fpga-programming-how-it-works-and-where-it-can-be-used/)
   7. [INTEL_FPGA_FOR_DUMMIES](https://www.intel.com/content/dam/support/us/en/programmable/support-resources/bulk-container/pdfs/literature/misc/fpgas-for-dummies-ebook.pdf)
   8. [FPGA_CONCEPTS](https://fpgaconcepts.wordpress.com/2012/05/29/dsp48/)
   9. [Getting_Started_with_VIVADO](https://engr210.github.io/projects/vivado_tutorial.html#creating-a-vivado-project)
   
   Reminder !!! in HDL , you're describing a piece of hardware logic not a software , so don't consider HDL as just another programming language.
   
 # VERILOG 01 
  Here are some of the resources for learning about VERILOG HDL 
  1. [CHIP_VERIFY](https://www.chipverify.com/verilog/verilog-tutorial)
  2. https://acg.cis.upenn.edu/milom/cis371-Spring13/lab/textbook-verilog-tutorial/VOL/main.htm ( This one would surely help you master the concepts of verilog HDL)
  3. https://verilogguide.readthedocs.io/_/downloads/en/latest/pdf/ 
    ( This one is quite underrated for beginners , you can jump directly to overview(chapter 02 , 
     staring the verilog section) , as in chapter 01 , author uses the schematic entry so needn't go through it , if you're planning to learn using HDL, but its worth      looking at how schematic capture tool works too ).
  3. https://people.ece.cornell.edu/land/courses/ece5760/Verilog/Verilog_index.html
  4. http://www.sunburst-design.com/papers/   ( For learning about Verilog , System verilog design methodologies , UVM and many more advanced concepts ).
  5. https://www.idc-online.com/technical_references/pdfs/electronic_engineering/RTL_Coding_for_Logic_Synthesis.pdf ( Synthesizable constructs in RTL coding)
  6.  [Intro to Verilog I.pdf](https://github.com/jogeshsingh/Learning-about-FPGA-DESIGN-/files/10299755/Intro.to.Verilog.I.pdf)
  7. https://vlsicoding.blogspot.com/search/label/Digital%20Design
  8. [O1_SIGNAL](https://www.01signal.com/)

 # VHDL

  1. [Sythesizable_vhdl](https://www1.cs.columbia.edu/~sedwards/classes/2011/4840/vhdl.pdf)

 # SOC

 1. [LINK](https://www.cl.cam.ac.uk/teaching//1718/SysOnChip/pdfnotes/Notes-RevA-First-Half.pdf)

    
  # FPGA (online courses links & University lab access material)
  1. https://people.ece.cornell.edu/land/courses/ece5760/
  2. https://www.coursera.org/specializations/fpga-design ( You can also apply for financial aid ).
  3. https://www.coursera.org/learn/fpga-intro
  

   # FPGA (e-books)
   1. https://www.fpgakey.com/
   2. [Design_warrior_guide_to_fpga](https://blog.aku.edu.tr/ismailkoyuncu/files/2017/04/01_ebook.pdf)
   
   # FPGA (Verilog HDL coding examples)
   1. https://fpgacoding.com/
   
   # FPGA cool site
   1. https://fpga-systems.ru/ ( you can translate in english)
   2. https://projectf.io/posts/fpga-memory-types/
   3. http://fpgacpu.ca/
   4. https://hackernoon.com/getting-started-using-open-source-fpga-tools
   5. https://openfpga.readthedocs.io/en/latest/overview/motivation/
   
   # FPGA page 
   
   1. [R/FPGA](https://www.reddit.com/r/FPGA/)
   
   2. [VERILOG](https://www.reddit.com/r/Verilog/)
   
   3. [CPU_DESIGN](https://www.reddit.com/r/cpudesign/)

   4. [EEVBLOG_FPGA](https://www.eevblog.com/forum/fpga/)
   
   # The only person I have seen demonstrating FPGA Design in Depth ...
   
   Thanks to https://github.com/ZipCPU
  
   Take a look at his website..
  
   https://zipcpu.com/
   
   # Blogs
  
   1. [IC_DESIGN](https://icdesignwatch.blogspot.com/search/label/ASIC%20RTL)
   
   # Youtube channel 
   1. https://youtube.com/playlist?list=PL_N6Mn2-rIUL635vG1_Ju4Hu0mRV-S-VV (Digital RTL Design using Verilog)
   2. https://www.youtube.com/channel/UCRZQvLnnlkJ0vHXGwjNsfNw ( This one is quite good , avaliable in hindi too)
   3. https://www.youtube.com/@Nandland ( How can we forget about this one , the life saver to beginner like us )
   4. https://www.youtube.com/c/SimplyEmbedded ( yeah , the guy expalins very nicely , but at quite faster rate).   
   5. https://www.youtube.com/@fpgamadeeasy ( For someone coming from software world to understand verilog ).
   6. https://www.youtube.com/@FPGAZealot ( This one is pretty advanced ...)
   7. https://www.youtube.com/@ElectronicswithProfMughal ( Again , the life saver for beginner like us).
   8. https://www.youtube.com/watch?v=Kt-78I-NUgY&list=PL-iIOnHwN7NXw01eBDR7wI8KzGK4mu8Sr (good one , for practicing Verilog + Vivado Sofware).
       There are pretty many youtube series on computer architecture too, will soon be posting about ... but FPGAs are pretty different than CPU, so don't stick with          sequential systems only...
       Enough watching tutorials , then put some hands on HDL & FPGAs. 
     
  # Open source tool/websites for practicing HDL 
   1. [Edaplayground](https://www.edaplayground.com/home) ( you can login using your google account , but using that you'll have access to only few tools , others require industrial verified account ) .
   2. [HDL_BITS](https://hdlbits.01xz.net/wiki/Main_Page) ( this one is pretty good site , making your fundamentals strong is the one way out from here ).
   3. [Chip_dev](https://chipdev.io/)                     ( This one is a bit advanced , required some previous experience in writing HDL code , however beginner can try) .
   
   # DIGILENT/XILINX-AMD DOCS
   1.  [DIGILENT](https://digilent.com/reference/tag/doc?do=showtag&tag=doc)
   2.  [AMD_XILINX_VIVADO_SYNHESIS_GUIDE](https://www.xilinx.com/support/documents/sw_manuals/xilinx2022_2/ug901-vivado-synthesis.pdf)
  
   # Some Websites/Papers for RTL Design Concepts
   1. https://www.eng.biu.ac.il/temanad/files/2021/12/Synthesizeable-RTL-2021-22.pdf
   2. https://www.idc-online.com/technical_references/pdfs/electronic_engineering/RTL_Coding_for_Logic_Synthesis.pdf
   3. https://classes.engineering.wustl.edu/2012/fall/jee2600/Lectures/JEE2600-Lecture-10.pdf
   4. https://people.ece.ubc.ca/~edc/379.jan99/lectures/lec8.pdf
   5. http://smdpc2sd.gov.in/downloads/IEP/IEP%208/24-02-18%20Rejender%20pratap.pdf
   6. https://uweb.engr.arizona.edu/~rlysecky/courses/ece274-08f/uploads/Main/lecture11.pdf
   7. https://www.cs.ucr.edu/~vahid/dd/dd_vahid_slides_Sep28_2006/dd_vahid_slides_ch4_Sep28_2006_FV.pdf
   8. https://uweb.engr.arizona.edu/~rlysecky/courses/ece274-07f/lectures/lecture15.pdf
   9. https://uweb.engr.arizona.edu/~rlysecky/courses/ece274-08f/uploads/Main/lecture14.pdf
   10. https://ics.uci.edu/~harris/cs151/slides/dd_vahid_ch5.pdf

   ## Some MIT Papers on FSM Design

   1. [Link_FSM](http://web.mit.edu/6.111/volume2/OldFiles/www/f2018/handouts/L06_4.pdf)
   
  
   # FPGA TOOLS
    
   1. `Xilinx(AMD) VIVADO ( webpack edition is free to be installed)`.

      -[XILINX_AMD](https://www.xilinx.com/support/download/index.html/content/xilinx/en/downloadNav/vivado-design-tools/archive.html)
      
      - [DIGILENT_TUTORIAL_INSTALLING_VIVADO_VITIS](https://digilent.com/reference/programmable-logic/guides/installing-vivado-and-vitis)
      
      - For windows 10 -:   [Link](https://www.xilinx.com/member/forms/download/xef.html?filename=Xilinx_Unified_2020.3_0407_2214_Win64.exe)

      - for Linux      -:   [Link](https://www.xilinx.com/member/forms/download/xef.html?filename=Xilinx_Unified_2020.3_0407_2214_Lin64.bin)
      
      - How to install Xilinx VIVADO ?

      - watch this video -:
       [Link](https://youtu.be/yW7t28XaVEs)
     
   ### installed the vivado ?

   - Then watch this video to know,  how to get started with ---:

     [LINK](https://youtu.be/BBtD4PCXqlE)
      
   2. `Quartus prime lite Edition + Modelsim simulator( from Intel , is free to be installed)`

      - How to install Quartus prime lite edition tool ?

        watch this video  -:)

        [CHECK_HERE](https://youtu.be/HO7yOu0C6bA)
      
      - To get started with QuartusPrime Lite GUI -:
      
        [Link](http://www.cas.mcmaster.ca/~leduc/slides2d04/labs/QuartusTutorials/Quartus_Std_Introduction.pdf)
      
      - How to get started building the logic and simulating the design in Quartus + Modelsim ?
        watch this video -:)

        [CLICK_HERE](https://youtu.be/YSQnVqXt3do)
     
      - Reminder !! I am  suggesting only above tools because I have found it pretty easy to grasp the flow, there are many vendors
     
        [CHECK_HERE](https://hardwarebee.com/list-fpga-)   
       
        some offer free versions too, and some not.
     
        There are many open source tools too , but as far as learning is considered you can learn it from anywhere . 
      
      
      
   
      
 
 
 

