<!-- <center><img src="http://mooc.e-yantra.org/img/eYantra_logo.svg" alt="e-yantra_logo" style="scale:75%;" /></center> -->

<style>
.back{
	position: fixed;
	width: 250px;
	height: 250px;
	top: 50%;
	left: 50%;
    margin-top: auto; 
    margin-left: auto; 
	opacity: 0.15;
    z-index: -1;
	}
</style>
<!-- <img src="http://mooc.e-yantra.org/img/EyantraLogoMini.png" class="back"> -->


<center><h1>Task 1 C : Finite State Machine </h1></center>

<hr>
<b>Problem Statement :</b> Design a Finite State Machine in Verilog HDL to detect sequence/pattern <b>1094</b>, which is a sequence of four <b>decimal</b> numbers (1,0,9,4).
<hr>

<b>Description :</b><div align="justify" class="main"> <a name = "Resources"></a> In this task you will be designing a Finite State Machine (Sequence/Pattern Detector) using Verilog HDL to detect sequence 1094. The input to your design will be any random stream of <b>decimal</b> numbers from <b>0-9</b> (Eg: 1830249754810). You’ll design a FSM which detects the pattern <b>1094</b>, whenever this pattern is detected the output becomes HIGH. Step by step procedure is discussed below.</div>


> *__Important__ : Your FSM design should work on the positive edge of the clock as shown in the below images.*  

<img src="./Task_1_C/1.jpg"
        alt="project file"
        style="float: center; margin-center: 10px;" />  

<img src="./Task_1_C/2.jpg"
        alt="project file"
        style="float: center; margin-center: 10px;" />  

> *__Note__ : You are only allowed to modify the code/ block diagram wherever it is mentioned to do so. Modifying the restricted blocks of code/ block diagram will result in **Zero Marks** and/ or **disqualification** from the competition.*

<hr>
Project File : <u><a href="./project_files/fsm.zip" download>Download TASK 1 C</a></u>
<hr>

<b>Resources :</b> <a name = "Resources1">
<ul>
 <li><u><a href="https://www.tutorialspoint.com/digital_circuits/digital_circuits_finite_state_machines.htm" target="_blank">Mealy and Moore State Machine</a></u></li>
</ul>

***

<b>Steps :</b>  

<ol>
<li><p align="justify" class="main">Open fsm.qpf (Quartus Prime Project File) located in the fsm folder. Quartus Prime might take some time to load depending on the configuration of your PC.</p></li> 
<li><p align="justify" class="main">You will find the fsm.v Verilog HDL file already added to the project.</p></li>

> *__Note__ : This file is pre-added to the project by the e-Yantra team.*

<li><p align="justify" class="main">Double click on it to edit. You’ll find prewritten code where the module is defined. Edit this file to design the required State Machine. Use Verilog case statement to design and write your code such that Quartus Generates a State Machine. For that, you will have to properly declare State Variables of the State Machine and also perform State Assignments correctly.</p></li>
<li><p align="justify" class="main">Compile your design. <b>Processing > Start Compilation.</b></p></li>
<li><p align="justify" class="main">Now you can view a graphical representation of your designed State Machine in Quartus. <b>Tools > Netlist Viewers > State Machine Viewer.</b></p></li>

 <img src="./Task_1_C/3.jpg"
        alt="project file"
        style="float: center; margin-center: 10px;" />  


> *__Note__ : The above State Machine is not for detecting the sequence 1094. Also, this graphical State Machine will be generated in Quartus only if your Verilog HDL code is written in a way that Quartus understands it as a State Machine.*

<li><p align="justify" class="main">You can compare the State Machine which Quartus generated and the self designed State Machine. You can edit your Verilog code and repeat the above steps till the desired State Machine is generated.</p></li>

<li><p align="justify" class="main">Finally Run the RTL simulation. <b>Tools > Run Simulation Tool > RTL Simulation</b>. A new window will pop up after a few seconds and you will be able to see the results of your design in ModelSim Software. If your design is correct then you will see a <b>Congratulations</b> message in the transcript. Else you will see an <b>Error</b> message in the transcript.</p></li>

<li><p align="justify" class="main">You can also check waveforms and verify/debug your design.</p></li>

 <img src="./Task_1_C/4.jpg"
        alt="project file"
        style="float: center; margin-center: 10px;" />  

When <b>Output(Y)</b> and <b>Expected Output(exp_out)</b> match, there will be no errors in the design.

</ol>

 


<p align=center><b>…BestWishes!…</b></p>