# comp2300-assignment-1--build-and-extend-a-cpu-solved
**TO GET THIS SOLUTION VISIT:** [COMP2300 Assignment 1- Build and Extend a CPU Solved](https://www.ankitcodinghub.com/product/comp2300-6300-engn2219-assessments-assignment-1-build-and-extend-a-cpu-assignment-1-build-and-extend-a-cpu-implement-the-processor-microarchitecture-for-the-quac-isa-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;109302&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP2300 Assignment 1- Build and Extend a CPU Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Assignment 1: Build and Extend a CPU Implement the processor microarchitecture for the QuAC ISA

In this assessment you are going to complete a number of Digital files to a required spec, much like what you have already been doing in the labs.

The first part of this assignment builds upon the following labs:

Lab 1: Introduction Lab 2: ALU Lab 3: Registers Lab 4: Manual CPU Lab 5: Auto CPU Lab 6: Conditional Execution If you have not completed the tasks in the above labs or do not understand the content, we strongly recommend that you first complete the labs and then start the assignment.

VHDL / Verilog / Anything outside of Digital Some extensions prohibit the use of certain components, check the extension page for details Submissions that use any of the above will have marks deducted accordingly.

Resources If this is your first time reading the document then skip this for now and open links as necessary

This assignment has a few external pages that are linked to throughout the document, for quick reference, here they are in one spot:

QuAC ISA Definitions QuAC Individual Instruction Definitions Part 2 Extension Options QuAC Assembler Guide Design Document Guide Digital Style Guide Background You have been building the CPU from the ground up during the first six labs. The first part of this assignment will require you to submit the CPU that conforms to the QuAC ISA.

The second part is more open-ended and will require you to extend the base ISA in an interesting way.

Specification Part 1 (30 marks) For the first part of the assignment, your task is to deliver a CPU in Digital that implements the full QuAC ISA specification.

If you have already completed the first six labs that result in a CPU for the QuAC ISA, then congratulations! You have already completed the first part of the assignmentâ€¦ sort of. You still need to update the files in the assignment repo and ensure they are passing the tests there. We arenâ€™t going to refer to your lab repos, but it is fine for you to copy your components over.

Complete src/basic-cpu.dig to the full QuAC ISA specification and ensure it is passing all provided tests.

You src/basic-cpu.dig should contain only what is needed for Part 1. Your extension and further modifications will be completed in src/extendedcpu.dig. Students who further extend the src/basic-cpu.dig file will have marks removed accordingly.

Part 2 (70 marks) Outline The QuAC ISA is quite limited in its capabilities compared to established ISAs, such as ARM and RISC-V. We cannot write very interesting assembly programs to solve real-world problems. The primary limitations of QuAC ISA include:

Few logical and arithmetic operations Limited set of general-purpose registers ALU instructions cannot directly operate on immediate values Inability to conditionally execute on anything other than the zero flag Lack of a stack and dedicated push/pop instructions (this point relates to functions) Your objective in this part of the assignment is to extend the QuAC ISA in a meaningful manner. To this end, you should note that the QuAC ISA deliberately has large gaps in the specification:

Eight of the 16 possible operation codes (opcodes) are undefined. New instructions can thus use these opcodes and even define a new encoding format other than R-Mode or I-Mode. Bits [3] and [7] in the R-Mode encoding format are only defined if both are zero (allowing each R-Mode instruction to have three alternate meanings based on the values of bits [3] and [7].) One of the register codes is unused, allowing for another special purpose register (check here to see which register codes are used). Bits [4:15] in the flag register are unused. The outcome/behaviour of writing to the flag register is undefined. This means that you could define writing to the flag register in the usual fashion (if you for some reason wanted to set/clear the flag bits directly) or you could add a write-only register that shares the same register code as FL (reading register code 101 reads from FL, writing to register code 101 writes to the new register.) Your extension can broadly be whatever you like, but keep in mind that sophistication of the extension is part of the marking criteria.

Your CPU with ISA extensions must be backwards compatible with the base QuAC ISA. This means that any changes you make must:

involve new instructions using currently undefined opcodes or use undefined bits in existing instructions (or both) if it interacts with existing instructions it must explicitly be an improvement that does not change the expected outcome from the base ISA Extension Implementation and Testing To be able to demonstrate and test the capabilities of your extension, you must make any necessary additions to the quac.json assembler config file to add support for your extensions, such that anyone can use it on your submitted CPU. Remember that the base ISA must still work, so you cannot change any existing instruction configs.

Once this has been completed, you must write at least one assembly program, demo.quac, that demonstrates your extension.

For more help on this, check out the assembler guide page.

Design Report Your assignment will also require the submission of a &lt;1000 words design report describing the design decisions you made to implement the base ISA and your extension. More specifically, we would like to see:

A high level overview of your extension What modifications you have made to the ISA What is the key benefit(s) of your changes The implementation details about your modifications, eg: The required changes to the microarchitecture Impact of changes on the CPU A small walkthrough of the example program Analysis of the tradeoffs / limitations with your implementation You will need to successfully implement a complex extension backed up by an excellent design report to get a mark in the HD range. See more here.

Your design report should precisely describe your extension and its behaviour and encoding in a format similar to the full ISA description.

Note that we say &lt; 1000 words. If you feel you have addressed all of what has been asked of you in less words, please donâ€™t feel the need to hit 1000 words. You will end up writing a worse report by reducing the conciseness of it.

Complete src/extended-cpu.dig to the full QuAC ISA specification and then extend it based on the information provided above. Provide at least one assembly program demo.quac that demonstrates your extension (further files should be added and named accordingly, eg: demo-stack.quac). Finally, write a design report in report.md detailing your extension.

Deliverables Outline To successfully complete this assignment, the following files must be submitted:

src/basic-cpu.dig containing your CPU that implements the full QuAC ISA, but no extensions beyond that src/extended-cpu.dig containing your CPU that implements the full QuAC ISA and has been extended beyond the base capabilities quac.json containing the default quac instructions and any extra instructions, etc. that you have added demo.quac containing the QuAC assembly program that demonstrates your extension optional demo-XXXXX.quac containing further assembly programs that demonstrate other aspects of your extension report.md containing your &lt;1000 word design report optional assets/* containing any images you want to add in your report Additional Files / Sub-circuits We provide the files src/basic-cpu.dig and src/extended-cpu.dig as templates that contain only the dual-port memory module. You should build the CPU(s) in these files. For any other additional sub-circuits (e.g alu.dig, reg_file.dig, control_unit.dig), please place them in the src/ directory. If your part-1 or part2 use differing versions of these sub-circuits, then please name them appropriately.
