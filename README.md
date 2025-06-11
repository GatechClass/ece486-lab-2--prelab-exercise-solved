# ece486-lab-2--prelab-exercise-solved
**TO GET THIS SOLUTION VISIT:** [ECE486 Lab 2- Prelab Exercise Solved](https://mantutor.com/product/ece486-prelab-exercise-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115008&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ECE486 Lab 2- Prelab Exercise Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (3 votes)    </div>
    </div>
𝑌(𝑠) 25

𝐻(𝑠)=𝑈 (𝑠)=𝑠2+6𝑠+25

1. Develop an all-integrator block diagram for the transfer function H1(s). What are the damping ratio and natural frequency? What the poles of the system?

2. Simulate the all integrator block diagram using SIMULINK

a) Type simulink in MATLAB command line or click on the Simulink icon as shown

b) Click Blank Model. At the blank SIMULINK library file

c) Double click on the Model Window to open a field and type “integrator” as shown in (I) to select and place the Integrator block. Alternatively, click “Library Bowser”. Search “continuous” to find the Integrator block and drag it to the model browser as illustrated by (II-IV).

d) Repeat the same for other block elements including Gain and Sum (from “Math Operation”).

e) Place a Step block from Source library and To Workspace block from Sink library

Scope block approach as you have learned in Lab 01 to log the data to the workspace too)

g) Label the output of the first integrator y_dot by double-clicking on the line representing the output

h) Double click on the Gain block and set the appropriate values

i) Double click on the Step clock to set the following parameters.

<img draggable="false" role="img" class="emoji" alt="⚫" src="https://s.w.org/images/core/emoji/15.1.0/svg/26ab.svg"> Step time: 0;

<img draggable="false" role="img" class="emoji" alt="⚫" src="https://s.w.org/images/core/emoji/15.1.0/svg/26ab.svg"> Initial Value: 0;

<img draggable="false" role="img" class="emoji" alt="⚫" src="https://s.w.org/images/core/emoji/15.1.0/svg/26ab.svg"> Final Value: 1; <img draggable="false" role="img" class="emoji" alt="⚫" src="https://s.w.org/images/core/emoji/15.1.0/svg/26ab.svg"> Sample Time: 0

j) Double click on To Workspace block connect to the output and set the following parameters:

<img draggable="false" role="img" class="emoji" alt="⚫" src="https://s.w.org/images/core/emoji/15.1.0/svg/26ab.svg"> Variable name: y <img draggable="false" role="img" class="emoji" alt="⚫" src="https://s.w.org/images/core/emoji/15.1.0/svg/26ab.svg"> Save format: Array

k) Double click To Workspace block connected to y_dot and set the following parameters:

<img draggable="false" role="img" class="emoji" alt="⚫" src="https://s.w.org/images/core/emoji/15.1.0/svg/26ab.svg"> Variable name: y_dot;

<img draggable="false" role="img" class="emoji" alt="⚫" src="https://s.w.org/images/core/emoji/15.1.0/svg/26ab.svg"> Save format: Array

l) Set the simulation parameters by clicking on the Simulation menu and choosing Configuration Parameters, to:

<img draggable="false" role="img" class="emoji" alt="⚫" src="https://s.w.org/images/core/emoji/15.1.0/svg/26ab.svg"> Stop Time: 3 (chosen to capture the main response)

<img draggable="false" role="img" class="emoji" alt="⚫" src="https://s.w.org/images/core/emoji/15.1.0/svg/26ab.svg"> Type: Variable-step

<img draggable="false" role="img" class="emoji" alt="⚫" src="https://s.w.org/images/core/emoji/15.1.0/svg/26ab.svg"> Solver: ode45

<img draggable="false" role="img" class="emoji" alt="⚫" src="https://s.w.org/images/core/emoji/15.1.0/svg/26ab.svg"> Max Step Size: 0.001(Smaller max step sizes give smoother responses, but take longer to compute)

<img draggable="false" role="img" class="emoji" alt="⚫" src="https://s.w.org/images/core/emoji/15.1.0/svg/26ab.svg"> Click on Data Import/Export and uncheck the Limit data points to last box.

m) Run the simulation by clicking on the Simulation menu

3) In the MATLAB workspace, you will find three variables: tout, y and y_dot. SIMULINK always saves the time vector as tout. Plot the variable y and y_dot using tout as the time axis.
