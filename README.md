# Errata

(Odds and Ends)

<img src="Images/OddsAndEnds_cropped.jpg" alt="Odds and Ends" width="1280" height="377">

***

Welcome to the group's repo hub section for information and repos that just don't really fit anywhere else! This includes codes that are used for tutorials and getting started, webpage items, class suggestions, conference schedules, etc.

<!-- commented out for now
<img src="https://github.com/ivsg-psu/ivsg_master/blob/master/images/PathPlanning_org.png" alt="Field Data Collection Org chart" width="1280" height="150">
-->


<!-- TABLE OF CONTENTS -->
# Table of Contents
<details open>
  <summary> Click to see/unsee </summary>

  <ol>
    <li>
      <a href="#copy-and-paste-items">Copy And Paste Items</a> 
      This includes the .gitignores we use, list of GitHub IDs for the team, etc.
    </li>
    <li>
      <a href="#tutorials-and-general-use-codes">Tutorials and General Use Codes</a> 
      This includes how to use GitHub, debugging tools, the FuncE gen auto-code generator, using MATLAB with Python, and coding challenges / exercises repo (public).
    </li>
    <li>
      <a href="#publication-odds-and-ends">Publication Odds And Ends</a> 
      This includes a list of our planned publications, calls for papers, journals we publish in.
    </li>
    <li>
      <a href="#student-competitions">Student Competitions</a> 
      A list of student competitions that the team may be involved with.
    </li>
    <li>
      <a href="#group-webpages">Group Webpages</a> 
      A links to the codes used to maintain the team's webpages.
    </li>
    <li>
      <a href="#suggested-classes">Suggested Classes</a> 
      Confused about what classes to take? Read here.
    </li>
    <li>
      <a href="#collaborators-at-penn-state ">Collaborators at Penn State </a> 
      A list of faculty at Penn State that you may not know of into automation. This is useful for PhD students looking for committee members!
    </li>
    <li>
      <a href="#committees-and-service ">Committees and Service Activities Related to the Group </a> 
      A list of of organizational committees that students might become involved with to gain visibility in our research areas.
    </li>
    <li>
      <a href="#fun-stuff">Fun Stuff</a> 
      Goofy items.
    </li>
  </ol>
</details>

<a href="#odds-and-ends">Back to top</a>

***

# Copy And Paste Items

<!-- COPY AND PASTE ITEMS -->
### The .gitIgnore for MATLAB
You can find .gitignore files [here](https://www.toptal.com/developers/gitignore). For MATLAB, we use the following:
```
# GITIGNORE template for MATLAB and SIMULINK
# Windows default autosave extension
*.asv

# OSX / *nix default autosave extension
*.m~

# Compiled MEX binaries (all platforms)
*.mex*

# Packaged app and toolbox files
*.mlappinstall
*.mltbx

# Generated helpsearch folders
helpsearch*/

# Simulink code generation folders
slprj/
sccprj/

# Matlab code generation folders
codegen/

# Simulink autosave extension
*.autosave

# Simulink cache files
*.slxc

# Octave session info
octave-workspace
```

### GitHub User IDs for the team
Here's a list of all the team member's user IDs for GitHub:

```

ivsg-psu - the "master" account for the team
prof-s-brennan - Dr. B's personal account (often linked into repos so he can personally edit)

Students (in alphabetical order by last name):
Mariam-Abdellatief - Mariamv Abdellatief (Summer '23)
pamin1 - Pranchit Amin (2024+)
IsaiahAdu - Isaiah Adu
Saif5241 - Saif Alameri
proofman82542 - Phakphum Artkaew
bwspsu - Wushuang Bai
aneeshbatchu - Aneesh Batchu
cbealbu - Prof. Craig Beal (Bucknell)
gnbodenschatz - George Bodenschatz
XinyuC - Xinyu Cao
cxchen@gmail.com - Prof. Cindy Chen (UML)
jcserns - Jack Csernica
McDeLa - Micah DeLattre
andespar15 - Andres Enrique Esparragoza (SHC honors student, graduating May 2024)
DanFescenmyer - Dan Fescenmyer
liminggao - Liming Gao
gabrielg78 - Gabriel Gayoso (2023+)
shashankgarik - Shashank Garikipati
sjharnett - Steve Harnett
Maomaodeweiba - Yanen Huang
bhavya5164 - Bhavya Jain
faisal1125 - Faisal Katibi
KazandjianV - Vahan Kazandjian
Justink21 - Justin Kerr
abelkim0909 - Abel Kim
beichenningxue - Ruiji Liu
stephenrm - Stephen "Steve" Maransky
msvsprasad - Satya Maddipatla
JMitro - Juliette Mitrovich
esolay - Emilio Olay
mikpsu - Michael "Mike" Pagan
emp212 - Evan Pelletier
marcusputz058 - Marcus Putz
cdrahn1506 - Prof. Chris Rahn
ElijahJRivers - Elijah Rivers (Summer '24)
IndyGPS2 - Natalie Rudisill
mustasalau - Mustapha Salau 
juliansim1729 - Julian Sim
ysun8 - Yao Sun
nickv22 - Nick Vitagliano
joshsingler - Joshua Singler
mariuspsu - Marius Tanase
Vaishnavi-Wagh - Vaishnavi Wagh

```          
<a href="#odds-and-ends">Back to top</a>

***


# Tutorials and General Use Codes

<!-- TUTORIALS AND GENERAL USE CODES -->
<details closed> 
  <summary> Click to see/unsee </summary>
  <ul>
    <li>
      <a href="https://www.datree.io/resources/github-best-practices">
      How to use GitHub
      <br>    
      </a>
      This is an intro on managing repos. We aren't the best at it, but practice will help.
      <br>   
    </li>
    <li>
      <a href="https://learngitbranching.js.org/">
      How to use Git CLI (interactive tutorial)
      <br>    
      </a>
      This tutorial shows you what’s happening with the branchces and commits in a repo as you run Git terminal commands in your browser.  The Git GUI is pretty good for the majority of use cases, but it lacks some of the features and levels of control you you get with the Git CLI (command line interface).
      <br>   
    </li>
    <li>
      <a href="https://www.conventionalcommits.org/en/v1.0.0-beta.2/">
      Github Conventional Commits 
      <br>    
      </a>
      This introduces the convention about how to write a commit message when you push update into repo. Please follow this convention!
      <br>   
    </li>
    <li>
      <a href="https://github.com/ivsg-psu/Errata_Tutorials_ReadmeTemplate/wiki">
      Errata_Tutorials_ReadmeTemplate 
      </a>
      A readme template that should be a starter for all repos. 
      <br>
    </li>
    <li>
      <a href="https://github.com/ivsg-psu/Errata_Tutorials_DebugTools/wiki">
      Errata_Tutorials_DebugTools (PUBLIC)
      </a>
      Common tools used for debugging MATLAB codes including input checking, print to workspace, and similar functions. 
      <br>
    </li>
    <li>
      <a href="https://github.com/ivsg-psu/Errata_Tutorials_FuncEGen/wiki">
      Errata_Tutorials_FuncEGen 
      </a>
      This is the private repo for the FuncEGen codes, e.g. codes for Functions-->Electronically Generated (FuncEGen). These auto-create functions almost instantly with cleanly formatted layouts, headers, etc.  
      <br>
    </li>
    <li>
      <a href="https://github.com/ivsg-psu/Errata_Tutorials_CodeExercises/wiki">
      Errata_Tutorials_CodeExercises (PUBLIC)
      </a>
      This is the public repo filled with coding challenges for new students. 
      <br>
    </li>
    <li>
      <a href="https://www.mathworks.com/campaigns/offers/matlab-python-cheat-sheets.html">
      Using MATLAB alongside Python
      </a>
      A link to MathWorks' website showing common tools to bridge MATLAB and Python 
      <br>
    </li>
    <li>
      <a href="https://github.com/ivsg-psu/Errata_Tutorials_MATLABPlotLib">
      Errata_Tutorials_MATLABPlotLib
      </a>
      Plotting tools developed in the team for special plotting needs.
      <br>
    </li>
    <li>
      <a href="https://opensource.com/article/20/4/plot-data-python">
      Plotting tools in Python
      </a>
      A link comparing plotting utilities for Python 
      <br>
    </li>
    <li>
      <a href="https://code.visualstudio.com/">
      Visual Studio Code
      </a>
      It is a light editor for Windows, Linux and macOS, and it can support debugging, syntax highlighting, intelligent code completion, snippets, code refactoring, and embedded Git. 
      <br>
    </li>
    <li>
      <a href="https://www.vim.org/">
      Vim
      </a>
      A light, text-based editor for Windows, Linux, and macOS.  It is most valuable to the group for its portability as it does not require a GUI desktop environment and can be run over SSH with undetectable lag. It can be difficult to learn but is rewarding for the potential editing speed it offers. 
      <br>
    </li>
    <li>
      <a href="https://github.com/ivsg-psu/Errata_Tutorials_PuttingTestTrackImageInAPlot">
      Errata_Tutorials_PuttingTestTrackImageInAPlot
      </a>
      (DEPRECATED) This is a tutorial and example of inserting the test track image into a MATLAB plot background, so that the XY coordinate plot in the figure corresponds to a location on the image, to see what the vehicle is doing. MATLAB now has tools that can do this automatically as of R2019a. For the up-to-date version, see the FieldDataCollection area, specifically: 
      <a href="https://github.com/ivsg-psu/FieldDataCollection_VisualizingFieldData_MapPanAndZoom/wiki">
      FieldDataCollection_VisualizingFieldData_MapPanAndZoom
      </a>
      <br>
    </li>
  </ul>


</details>

# Converting MS Word to Markdown with Pandoc

The documentation and installation instruction can be found in the site below:
https://pandoc.org/

Using Pandoc is fairly easy. It is a command line tool that can be accessed from PowerShell in Windows. Below is an example use case, where a MS Word file example.docx is converted to the markdown file example.md. The images in the MS Word document are placed in the ./images./example_images directory.

`pandoc -f docx -t markdown --extract-media ./images/example_images .\example.docx -o .\example.md`

<a href="#odds-and-ends">Back to top</a>

***

# Publication Odds And Ends

<!-- PUBLICATION ODDS AND ENDS -->

## Planned publications
Planned publications should follow the format:<br>
(Student name): <br>
Title: (title)<br>
Venue: (venue)<br>
Due date: (date the DRAFT should be sent to co-authors)<br>
Draft Abstract: (a few sentences what the paper is about - start with why people should care, then what problem we are solving, then our methods to solve the problem, then summary of how our results are useful.)<br>
<br>
Satya: <br>
Title: "AVAR-based estimation of variance changes in automotive sensor applications" <br>
Venue: To be submitted to International Journal of Prognostics and Health Management. <br>
Due date: Abstract to Dr. B by Dec 15th. 
Abstract due: Jan 15th; Paper due: April 30th.<br>
Abstract: Many automotive applications utilize sensor information to estimate changes in vehicle characteristics including variance and averages. This paper presents a methodology to systematically estimate, in real-time, changing signal characteristics with examples motivated by automotive systems. The method used in this work is based on the recently-developed fast Allan-Variance methods, or FAVAR, which determines optimum windows of data that minimize the variance in the resulting signal. Application examples include estimation of traffic flow, wheel speed sensing, and lane estimation.<br>
<br>

Satya: <br>
Title: "Identifying locations in traffic network where vehicles are most likely to skid" <br>
Venue: To be submitted to 33rd IEEE Intelligent Vehicles Symposium (IV22). <br>
Due date: Extended summary and outline to Dr. B by Dec 15th and full paper by Jan 15th. 
Paper due: Feb 1st. <br>
Abstract: This paper presents how traffic simulations(1-DOF) fail to account for road properties like friction, grade, and curvature. It also demonstrates how higher DOF vehicle models will point out limitations in the traffic simulator's trajectory. <br>
<br>

Satya: <br>
Title: "AVAR-based estimation of friction in one dimension" <br>
Venue: To be submitted to 15th International Symposium on Advanced Vehicle Control (AVEC 2022). <br>
Due date: Extended summary to Dr. B by Dec 15th. <br>
Abstract due: Jan 17th; Final manuscript due: June 6th. <br>
Abstract: <br>
<br>

Satya: <br>
Title: "Clustering based on Allan variance" <br>
Venue:  <br>
Due date: <br>
Abstract due: <br>
Abstract: This paper talks about clustering a signal based on its noise properties using Allan variance to identify context, in other words to identify the active input. <br>
<br>

Wushuang: <br>
Title: "How does typical wear-and-tear on traffic control devices affect sensing of the same objects by autonomous vehicles?" <br>
Venue: To be submitted to 15th International Symposium on Advanced Vehicle Control (AVEC 2022). Due date to Dr.B: (Extended summary) 2021-12-17.<br>
Abstract: Most of autonomous vehicles use LiDAR and camera for purposes of localization and perception, and these tasks may become hard in construction zones due to the complexity of driving environment. Furthermore, the degradation of the traffic objects, such as traffic signs, traffic control devices and operator vests etc. may cause the tasks to be even harder, and how degradation, i.e., wear and tear affect LiDAR and camera performance yet remains unknown. This paper presents experimental work implemented on a test track to verify how degradation occurred on common traffic objects can affect reflectivity of LiDAR measurements and classification results of camera measurements. <br>

<br>
Student Name(s): Seth Tau & Michael Pagan (possibly)<br>
Title: Determining Maximum Maneuvering Speeds for Autonomous Off-Road Vehicles in Limited-Friction Obstacle Fields<br>
Venue: Journal of Autonomous Vehicle Systems (JAVS)<br>
Due date: April 2021? (flexible)<br>
Draft Abstract: An important performance metric for any autonomous vehicle is the speed at which it can maneuver around obstacles (i.e., the maneuvering speed). The maneuvering speed of an autonomous vehicle is primarily limited by the characteristics of the obstacle field (size and spacing), the response time of the vehicle to sensor information (i.e., vehicle system closed-loop time delay), and the available friction, especially for off-road maneuvering. An important research question is what the quantitative relationship is relating these three factors to the speed at which a vehicle can maneuver through an obstacle field. This paper examines this relationship through a series of computer simulations and uses the statistical results to determine equations that approximate the maneuvering speed given an obstacle map, time delay, and available friction. The simulations are performed on a multitude of pseudorandom obstacle fields with specified map characteristics, frictions, and vehicle system time delays. The simulations account for friction and time delay by dilating the obstacles to generate regions around obstacles where maneuverability of the vehicle is limited due to proximity to the obstacle. This work treats those dilations as impassable regions and continues to increase vehicle speed until those regions make traveling through the obstacle field infeasible. The results of this paper confirm the expected trends that smaller gap spacing between obstacles, greater time delay, and lower friction reduce maneuvering speed. More importantly, this work provides a way of quickly estimating the maneuvering speed of a vehicle moving through a two-dimensional limited-friction obstacle field without performing any simulations.<br>

<br>
Student Name(s): Seth Tau & Steve Harnett (possibly) <br>
Title: The Effects of Mapping Error on Path Efficiency with Variable Sensor Range <br>
Venue: Journal of Terramechanics (JoT) <br>
Due date: April 2021? (flexible)<br>
Draft Abstract: The goal of path planning is to navigate around obstacles from a start point to a goal and algorithms for path planning therefore require maps of obstacle fields; however, there may be uncertainty in these maps which affects the distance traveled. The majority of research related to obstacle field uncertainty has studied the effect of errors on the path planning and navigation process, but relatively little work has focused on understanding the impacts of uncertainty on the final path. This paper describes the relationship between uncertainty in the initial map used for path planning through an obstacle field and the final traversal distance through the field as determined through computer simulations. The dimensionless representation of map error can encompass many different sources, such as GPS errors in the data collection process or location uncertainty in mobile obstacles. The work in this paper determines these relationships by generating a multitude of pseudorandom obstacle fields with specific map characteristics, adding uncertainty to the map, and then path-planning through the field. During the path-planning process, obstacles within a given sensing range of the vehicle are considered sensed and the mapping uncertainty of those obstacles is removed. The results of this paper show that in situations where there is significant error in the mapped obstacle size, most vehicles with reliable on-board sensors will perform better if the obstacle size is underestimated rather than overestimated. Additionally, as the error in the original map increases, it reaches a point where the vehicle can no longer plan paths without a long-range sensor. The results also indicate that there is a limit in sensing range, beyond which the usage of longer-range sensors results in negligible reductions in final traversal distance. All these results are generalized using non-dimensional parameters so that the results can easily be extended to vehicles and environments of any scale. <br>
<br>
Student Name(s): Steve Harnett <br>
Title: Estimation of Navigation Cost from Geometric Obstacle Field Parameters <br>
Venue: GVSETS <br>
Due date: March 2022<br>
Draft Abstract: In the field of ground robotics, the problems of off-road navigation and obstacle avoidance are often assessed in terms of the cost of navigating through a given environment.  Traversal cost is often defined in terms of the required fuel, required travel time, and imparted mechanical wear to drive the selection of an optimal route. Prior work has shown that obstacle field complexity and navigation cost can be abstracted into quantitative dimensionless parameters, but determining the cost parameters requires running repeated path planning simulations.  This work presents a method for estimating navigation cost solely from geometric obstacle field complexity measures, eliminating the requirement to run a path planner in a simulation environment.  From geometric parameters of obstacle shape and size, an estimate for the deflection required to navigate around the obstacle is derived.  This is then combined with an estimate for the number of times the path will have to deflect around an obstacle during a given mission, based on occupancy and density parameters of the obstacle field.  This cost estimate has been evaluated on numerous simulated obstacle fields to generate data of estimated cost versus obstacle field complexity.  This data was compared to cost versus obstacle field complexity data generated by running a path planner over simulated obstacle fields while computing the actual cost.  This comparison proves the estimated cost algorithm to be a reasonable approximation .    Both data sets could be used to estimate traversal cost from an obstacle field with a known complexity, however the method presented here also allows for estimation of traversal cost for a specific obstacle field and mission, without requiring the computational time and resources necessary to run path planning simulations.   Additionally, it is agnostic of the planning algorithm as it uses a geometric approximation of the optimal route.   <br>
<br>
Student Name(s): Seth Tau <br>
Title: The Effects of Sensing Error on Path Planning Efficiency <br>
Venue: Journal of Autonomous Vehicle Systems (JAVS) <br>
Due date: April 2021? (flexible) <br>
Draft Abstract: The goal of path planning is to navigate obstacle fields from a start point to a goal, which often requires maps of the obstacle fields for use with path-planning algorithms. However, the maps are not always accurate, so vehicle control systems often utilize sensors to verify or correct map information. Unfortunately, sensor can be subject to errors that may confound the sensor reading and potentially add error to the maps. Most of the research in this area has focused on how to mitigate or correct these errors, but there has been less work that focuses on how these errors change the path taken by the vehicle. This work aims to determine how sensor error changes the length of the path taken by a vehicle driving through an obstacle field. Specifically, this paper describes the relationship between sensing uncertainty during the obstacle-field-traversal process and the final traversal distance through the field as determined through computer simulations. The sensing error types presented in this work can cover a variety of different sensor types, such as GPS, LIDAR, radar, and camera. The results are determined by generating a variety of pseudorandom obstacle field maps with certain characteristics and then performing vehicle traversal simulations. During these simulations a path is planned, the vehicle begins to follow that path, and then the map is updated as the vehicle and its sensor move through the environment. As the sensor moves through the obstacle field it provides new information with potential errors to the map and then a new path is planned based on the updated map. This process continues until the goal is reached or path planning becomes infeasible. The results of this work show that an increase in sensing error correlates with an increase in path length and that sensing error tends to have a larger effect on path length for more closely spaced obstacles. Additionally, the results indicate that when selecting a sensor for obstacle field traversal sensor accuracy may be more important than sensor range <br>
<be>

<br>
Student Name(s):Liming Gao <br>
Title: Box-based Representation and Data Sharing of Road Surface Friction for CAVs <br>
Venue: 2022 Road Safety and Simulation International Conference <br>
Due date: November 29, 2021 (published)<br>
Draft Abstract: This paper presents a road friction map generation strategy by aggregating the measured road-tire friction coefficients along the individual trajectories of CAVs through a shared roadside database. An insight of this work is that the friction data can be represented compactly by regions defined by a friction value within the region and the boundaries of the region in space.<br>
<br>

<br>
Student Name(s):Liming Gao <br>
Title: Vehicle Model Predictive Trajectory Tracking Control with Uncertainty of Friction Preview <br>
Authors: Liming Gao, Craig Beal, Satya Prasad Maddipatla, Juliette Mitrovich, Sean Brennan, etc.<br>
Venue: IEEE Transactions on Control Systems Technology <br>
Due date: August 2022 (flexible) <br>
Draft Abstract: In order to utilize a vehicle's handling capability up to the limits of behavior, road friction has to be known. However, the friction estimation uncertainty is always present in a real environment(to be specific, ). To guarantee accurate path tracking with stability at high speed in such real situations, the controller is required to be robust against uncertainty. To address this challenging problem, firstly, during the longitudinal speed planning, the margins between the strict estimated limits versus designed limits for more complicated target path shape and road friction distribution part are identified. Meanwhile, a stability margin based on the stability envelope used at the MPC lateral controller is defined. Then, the impact of preview data quality on the feasibility and performance of the path following controller is analyzed. <br>
<br>

<br>
Student Name(s):Liming Gao <br>
Title: Shared MPC steering and speed control for path tracking with Cyber-Physical based road friction preview <br>
Venue: IEEE Transactions on Control Systems Technology <br>
Due date: January 2022 (flexible) <br>
Draft Abstract: The MPC-based shared controller is designed to track the reference trajectory while matching the driver’s throttle and steering commands whenever safe. A model predictive control (MPC) scheme determines at each time step whether the current driver command allows for a safe vehicle trajectory, intervening only when such a trajectory will exceed the stability envelope. In this way, the controller shares control with the driver in a minimally invasive manner while tracking the desired path and preventing loss of control. <br>


<br>
Evan Pelletier:<br>
Title: "Platoon Formation Decision Making: Physics Predictions versus Predictive Control" <br>
Venue: IEEE Transactions on Intelligent Vehicles <br>
Due date: Abstract to Dr. B by Nov. 22nd. Full paper Dec. 13th. (Journal submission flexible)<br>
Abstract: Vehicle powertrain simulations show that platoon formation scenarios are not equivalent at different highway cruise velocities. The potential fuel savings for a follower vehicle chasing a leader on a shared route decrease at faster chase velocities, particularly for routes with sections of steep road grade. These simulations are compared to predictions from physics-based energy equations to show where the physics equations are good predictors of advantageous chase scenarios. After deciding on a range of reasonable chase velocities, an algorithm is developed to set the follower’s chase velocity based on route information known a priori such as terrain, traffic and wind conditions.<br>
<br>

<br>
Matt Taylor:<br>
Title: "Airborne roll control of a high-speed off-road vehicle using spoiler-mounted thrusters" <br>
Venue: To be submitted to 15th International Symposium on Advanced Vehicle Control (AVEC 2022). [2022 AVEC website](https://avec2022.org/)<br>
Due date to Dr.B: (Extended summary) 2021-12-17.<br>
Abstract: At high speeds, off-road vehicles can be airborne a significant amount of time during the traversal of a course. However, while airborne, the vehicle loses the ability to steer, brake, or throttle due to the loss of contact between tires and ground. At high speeds, on-road vehicles typically use spoilers to increase ground forces - particularly on the rear axle of the vehicle. However, for off-road vehicles, the vehicle motion is often limited in speed due to the difficulty in controlling the landing orientation of the vehicle. This paper develops a control input technique that utilizes thrusters mounted to the spoiler of an off-road vehicle to affect ground forces during ground contact, and as well control the roll orientation of the vehicle while airborne. Simulations and real-world implementation results are shown for a 1/5-scale high-speed off-road autonomous vehicle. <br>
Steps: <br>

1. Develop a model for roll motion of the vehicle. What are the eigenvalues of the dynamics of roll (e.g. time constant). Use the model to calculate the amount of thrust needed to cause the vehicle to change its orientation in mid-flight, e.g. 90 degrees of roll within 1 second.<br>

2. Build the spoiler with UAV thruster control (e.g. motors that are powerful enough to change the orientation)<br>

3. Develop sensors to measure roll (e.g. an IMU)<br>

4. Do "drop tests" of the vehicle whereby you can demonstrate roll control<br>

5. Implement the controller on a simple microcontroller (Tensy 4.1 should work), repeat drop tests<br>

6. Perform field tests with the vehicle on ramps.<br>
<br>

<br>
Juliette Mitrovich: <br>
Title: Modeling the Variability in Real World Road Friction as a Function of Spatial Location <br>
Venue: <br>
Due date: <br>
Draft Abstract: When you are driving, the uncertainty of the road friction is constantly changing. For example, when it is icy and snowy out, the lateral uncertainty is high due to the fact that there is higher road friction in the tire tracks created by the vehicle in front of you than in between and outside of the tire tracks. Because of this, you, and the vehicle, know not to change lanes. A similar relationship exists between the road friction and the spatial location of the vehicle. Right before it snows/while it is snowing, it's safest to make a lane change under a bridge because that area has the highest friction. However, after it snows, it's safest to make a lane change before you go under a bridge because the friction is lower due to melting snow and the area being constantly shaded. This paper aims to model how the uncertainty of friction changes as a function of spatial location. <br>
<br>

<br>
Juliette Mitrovich: <br>
Title: Limiting Allowable Maneuvers on the Road as a Function of Friction Uncertainty <br>
Venue: <br>
Due date: <br>
Draft Abstract: Every maneuver a vehicle makes requires a certain amount of friction. If a maneuver, like changing lanes, is made without the right amount available, the vehicle will become unstable. In an ideal condition, there will always be enough friction to make a lane change. However, the ideal condition doesn't always exist because friction uncertainty changes with spatial location. However, if you can model the relationship between friction uncertainty and spatial location, you can design a controller to account for the constantly changing uncertainty bounds. By "converting" vehicle maneuvers to friction, you can compare the friction to the uncertainty margin, allowing the vehicle to know what maneuvers are safe based on where they are.  <br>
<br>

<br>
Juliette Mitrovich: <br>
Title: Spatially Varying the Weight on Constraints as a Function of Location <br>
Venue: <br>
Due date: <br>
Draft Abstract: When employing a vehicle controller, there is a distinction between the types of constraints that are applied, hard versus soft. Hard constraints are constraints that cannot be violated and soft constraints are constraints that can be violated. Normally, each constraint is fixed. However, whether a constraint it hard or soft largely depends on your spatial location. For example, if a vehicle is driving on the highway and it becomes unstable, crossing over the white line separating it from the median, the vehicle is always going to hit the median. However, if a vehicle becomes unstable on the highway, crossing over the dashed white lines separating the lanes, it will not always result in a crash with another vehicle. Sometimes there aren't any other vehicles on the road to hit, or a vehicle will swerve out of the way. This paper aims to model the relationship between the weight of constraints as a function of vehicle location. <br>
<br>


## Calls for Conference Papers and common Journals

[The conference calendar for the group](https://calendar.google.com/calendar/embed?src=l75aupdplp7m46rnbddlgfos40%40group.calendar.google.com&ctz=America%2FNew_York) is public. For more paper details, subscribe to the DSCD List for each year's information: https://groups.google.com/forum/#!forum/dscd-list

### IFAC Symposium on Advances in Automotive Control
Dear colleagues,

We would welcome your participation in the 10th IFAC Symposium: Advances in Automotive Control, AAC 2022, which will be held at The Ohio State University in Columbus, Ohio, USA  on August 28-31, 2022.  The event should provide a very good opportunity for presenting your recent research work, networking, and learning new challenges from industry. A CFP for the event is attached.

Due date for draft papers: 2022_02_14
[IFAC 10th Symposium on AAC website](https://car.osu.edu/AAC2022)


### Special issues

ATS Members:


Some members of our TC are organizing a special issue entitled “Advanced Diagnostics and Prognostics for Automotive Systems” in the International Journal of Prognostics and Health Management. Please see below for more details and consider submitting your recent work.


This special issue focuses on theory and application of diagnostics and prognostics (DnP) analytics and methods for condition monitoring, anomaly detection, and health management of automotive systems and their manufacturing processes. Articles addressing recent developments on the following topics are solicited, but not limited to:

 

•            DnP algorithms and methods for vehicle components such as propulsion, chassis, and electrical systems

•            DnP systems and methods for automated driving systems and connected vehicles

•            Fault mitigation for robust performance of vehicular systems

•            DnP systems for advanced automotive manufacturing processes

•            Emerging machine learning and verification techniques and their application in vehicle health management

•            Physics of failure mechanisms and modeling and simulation techniques

 

Key dates:

Abstract Due: January 15, 2022

Full Paper Due: April 30, 2022

 

Team of Guest Editors for the special issue:

Dr. Yilu Zhang, General Motors Research and Development, Warren, MI, US, yilu.zhang@gm.com

Dr. Xiaodong Jia, Research Assistant Professor, University of Cincinnati, Cincinnati, US, jiaxg@ucmail.uc.edu

Dr. Rasoul Salehi, General Motors Research and Development, Warren, MI, US, rasoul.salehi@gm.com

Dr. Jason Siegel, Associate Research Scientist, University of Michigan, Ann Arbor, MI, US, siegeljb@umich.edu

Dr. Shiyu Zhou, Vilas Distinguished Achievement Professor, University of Wisconsin, Madison, US, szhou@engr.wisc.edu

 

Submission Instructions:

Please submit your manuscripts (abstracts or full paper drafts) at the IJPHM website  https://papers.phmsociety.org/index.php/ijphm/about/submissions. Use the section “Comments for the Editor” to indicate that the article is being considered for publication in the Special Issue on Advanced Diagnostics and Prognostics for Automotive Systems.

 

If you have any questions, please email Yilu Zhang (yilu.zhang@gm.com) and me (rasoul.salehi@gm.com).

### GVSETS
The 14th Annual Ground Vehicle Systems Engineering and Technology Symposium (GVSETS) – Warfighter Technology Solutions for the Future

August 16 – 18, 2022

Suburban Collection Showplace - Novi, MI

 

Call for Abstracts: Deadline Friday April 1, 2022

In a world that is continuously shifting, enabling our warfighters to have access to the best capabilities available becomes paramount. These technology solutions are developed by academia, industry, and government: the challenge becomes integrating those solutions into current and future military ground vehicles. Therefore, the focus of the 2022 Ground Vehicle Systems Engineering Technology Symposium (GVSETS) is on developing warfighter technology solutions for the future fight. This live and in person event will serve as forum for engineers and scientists to connect and build relationships to solve the future challenge for our warfighters.  

 

The U.S. Army DEVCOM Ground Vehicle Systems Center (GVSC), as the lead integrator for DOD ground systems, invites you to submit a DRAFT PAPER** to NDIA Michigan’s 2022 GVSETS.  Your paper should detail your technical work that is helping to bring warfighter technology solutions into the future. 

 

DRAFT PAPER SUBMISSION DEADLINE – April 1, 2022
The GVSETS topics include, but are not limited to:

·         Advanced Materials and Manufacturing

·         Autonomy, Artificial Intelligence, and Robotics

·         Cybersecurity of Ground Systems

·         Digital Engineering / Systems Engineering

·         Modeling, Simulation, and Software

·         Power & Mobility

 

DRAFT PAPER SUBMISSION REQUIREMENTS

    Submission Deadline – April 1, 2022
    Content and format requirements:

        Papers require a minimum of 5 pages.
        Papers should be complete to include background/motivation, supporting data, figures, tables, conclusions and references.
        Papers must demonstrate relevance to the ground vehicle development missions of the U.S. Army and/or U.S. Marine Corps (USMC).
        Papers must conform to the format provided in the Word or LaTeX templates.
        Papers SHOULD NOT be commercial in nature or have a marketing emphasis.

    Operations Security (OPSEC) requirements: 

§  All papers must be unclassified and releasable to the public.

§  Papers authored/co-authored by government employees or that contain work funded by the government must go through the OPSEC approval process.

§  Papers which require OPSEC must contain the “Distribution A” statement and OPSEC tracking number/date upon submission.

§  Submissions imply the intent of at least one author to attend GVSETS and present the paper.

§  All attending paper authors are responsible for their own registration fee.  Keep in mind all government attendees are free.

  IMPORTANT DATES TO REMEMBER

    April 1, 2022 - DRAFT PAPER submission deadline *
    May 6, 2022 - Notification of acceptance 

    June 17, 2022 - Final paper submission *

    August 1, 2022 - Final presentations due *

    August 16, 2022 - Paper Presentation  

 

*This timetable does not include time for OPSEC review which is required by all USG papers.  Please allow two weeks for OPSEC process prior to submission dates.

 

** A change to note for GVSETS 2022:  Presenter selections will be based off of a draft paper review with a minimum of 5 pages.  Abstracts will not be accepted.

To submit a draft paper or for more information please click on the link below: Technical Papers (ndia-mich.org)
For more information, please contact Leslie A. Smith, CMP, Senior Director of Programs at (248) 353-0735, ext. 152 or gvsetstechsession@ndia-mich.org.
Leslie Ann Smith, CMP<br>
Senior Director of Programs & Budgets<br>
The Engineering Society of Detroit <br>
20700 Civic Center Drive, Suite 450 <br>
Southfield, MI 48076 <br>
248-353-0735, ext. 152 <br>
248-353-0736 fax <br>
lsmith@esd.org <br>
www.esd.org <br>

### The American Control Conference

2021 American Control Conference, Friday, May 26-28, 2021 in New Orleans, Louisiana

Typical schedule:
* Control Systems Letter (L-CSS) with ACC option submission deadline: July 1st to September 1st
* ACC manuscript and Invited Session Proposal submission deadline: September 14
* Acceptance Notification:  January 24, 2021
*  Final manuscript submission:  March 15, 2021

### The Control Systems Letters

The joint submission to IEEE Control Systems Letters and ACC 2021 will be possible from July 1 to September 1, 2020. Manuscripts submitted to the L-CSS with the ACC option will undergo a regular review as papers submitted to the Letters (so they should be submitted only to the L-CSS and not to the ACC). At the end of the first round of review, the reviews and the Associate Editor's report will be forwarded to the ACC Program Committee, which will use them to decide on the inclusion of these manuscripts in the program of the Conference. After the first cycle of review, the decisions about the acceptance or rejection of the manuscript for the L-CSS and for the ACC will be independent of each other. In particular, reviews and reports collected during a possible second round of review will not be forwarded to the ACC Program Committee.

Note that you can submit your paper through the Letters also if the paper will be part of an Invited Session at ACC 2021. In that case you should select "L-CSS and ACC Invited", as submission type. For more information about joint submission to L-CSS and ACC see, specifically, http://ieee-cssletters.dei.unipd.it/Page_authors.html

### The Roadside Safety and Simulation Conference
RSS2021: the dedicated website at https://www.nrso.ntua.gr/rss2021/ 

Typical schedule:
* Abstract submission (up to 500 words): 15th November
* Acceptance Notification:  
* Final manuscript submission: 

## Journals

### IEEE ITS

### ASME JDSMC

### The Journal of Autonomous Vehicle Systems
A new, possibly strong journal focused on ground vehicle mobility

<a href="#odds-and-ends">Back to top</a>

## Thesis Ideas 
1. AR camera system on truck

2. Automated lane tracking

3. Parallel park a tractor-trailer

4. Digitally map downtown state college for driving simulator

a. Subcategories:

i. Image processing

ii. Realtime driving

iii. Blurring other vehicles out

iv. Correcting for lighting changes

v. Processing LIDAR data

vi. Make road look smooth (IRI Index)

vii. Create functioning traffic lights in photographic environment

viii. Calculate the position of the sun based on the position of a vehicle to determine if the vehicle is missing any road signs

5. Subject testing: Does AR & VR change drivers’ perception of risk?

6. Mapping friction of the test track using a steer-by wire racecar

7. Automating a wheelchair to follow a predetermined path

a. Training

b. Operating with human assistance

c. Automated operation

8. Interface traffic simulator with driving simulator

9. Data fusion between camera and radar

10. Implement safety feature for truck radar

a. The radar can fail to detect a stationary vehicle when traveling around a curve

11. Department project: RC vehicle community with overhead camera 
***

# Student Competitions

<!-- STUDENT COMPETITIONS -->
<details closed> 
  <summary> Click to see/unsee </summary>
  <ul>
    <li>
      <a href="https://www.sae.org/attend/student-events/autodrive-challenge/">
      SAE AutoDrive II (two) Competition
      <br>    
      </a>
      Our group is heavily involved with this team with the competition running from 2021-2025.
      <br>   
    </li>
    <li>
      <a href="https://f1tenth.org/index.html">
      The F1-Tenth competition
      </a>
      This is a competition organized within the IROS program that uses 1/10 scale vehicles. It's a neat, easy way to get started in chassis vehicle control. 2020 competition was at Las Vegas but we do not know when competitions are held beyond this.  
      <br>
    </li>
    <li>
      <a href="https://ieee-itsc2020.org/uas-collected-traffic-data-analysis-uas4t-competition-2/">
      IEEE ITSC UAS Collected Traffic Data Analysis (UAS4T) Competition 
      </a>
      The IEEE International Conference on Intelligent Transportation Systems conference has hosted in 2019 and 2020 a student competition on Unmanned Aerial Systems used to monitor traffic behavior, and the goal is to integrate UAS measurements into a traffic simulation and use that simulation to predict traffic flows. 
      <br>
    </li>
  </ul>

</details>

<a href="#odds-and-ends">Back to top</a>


***


# Group Webpages

<!-- GROUP WEBPAGES -->
<details closed> 
  <summary> Click to see/unsee </summary>
  <ul>
    <li>
      <a href="https://github.com/ivsg-psu/Errata_AutoWeb/wiki">
      Errata_AutoWeb   
      </a>
      This is the MATLAB code and resulting html files that auto-generate our group's webpage.
      <br>   
    </li>
    <li>
      <a href="https://github.com/ivsg-psu/Errata_ConnectedVehicles_Webpage">
      Errata_ConnectedVehicles_Webpage
      </a>
      This is the HTML code for the ConnectedVehicles webpage.
      <br>   
    </li>
    <li>
      <a href="https://github.com/ivsg-psu/Errata_IVSG_Webpage">
      (DEPRECATED) Errata_IVSG_Webpage
      </a>
      This takes you to the OLD repo for the IVSG webpage. The webpage share is at: \\E5-MIS-MWS\web_me_toboldlygo$ A copy of the full site can be edited by students via an invite to the folder on OneDrive labeled: IVSG_Webpage. Note that the AutoWeb code now maintains this data, so manual entries are automatically overwritten each time the generation code is run.
      <br>
    </li>
  </ul>

</details>

<a href="#odds-and-ends">Back to top</a>


***

# Suggested Classes
A comprehensive list of controls-focused classes can be found at the site: [https://sites.psu.edu/controls/home/graduate-courses/](https://sites.psu.edu/controls/home/graduate-courses/). The suggestions below have more detail, but the above site is better maintained and much more comprehensive.

## For undergrads
First, decide if you are going to grad school or not. The importance of this decision is that some courses that prepare you best for grad school have little to do with mechatronics, automation, control, or robotics - at least, not at first. Second, decide if you are specializing in theory or application as the courses for these do not overlap sometimes.

### Undergrad not planning on grad school:
**ME 456 Robotics**
This is an all-around solid introduction to robotics with focus particularly on the "classical" definition of motion control of robot arms and kinematics of ground robots. This course is heavy on matrix multiplication and coordinate transforms, but does cover other basic principles such as decision architectures, path planning, implementation considerations, etc.

### Undergrad planning on grad school:
**Statistics** and **Linear Spaces**

These two courses are offered in the stat and math departments, and are core classes that undergraduates miss compared to other universities - particularly when comparing US students to international students. Without these courses, many topics within graduate school are much more difficult to absorb. If possible, a strong suggestion for undergrads is to get a math minor, particularly if focusing on the theory aspects of automation which is quite mathematical.

### Undergrad focus on Applied automation
**ME 454: Mechatronics** This is the core "hands-on" course in the automation field. A must-have to understand how to design automation hardware implementations.

**ME 481 - Computational Machine Dynamics** - Prof. Sommer teaching this, heavy math but not too challenging, strong emphasis on simulation tools and validation between simulation results and physical experimentation/expectation.

**Digital Control** (aka "Discrete" control) - This is a course typically taken right after ME 455 (or equivalent) that discusses controller design in discrete time rather than continuous time. The differences between these domains can seem large at first (and some are indeed large), but a good digital control course will emphasize the similarities.


### Undergrads with Theory Emphasis

**ME 455:Feedback Control** (aka "Classical Control")

**ME 555: Linear control** (aka "Linear Systems") 

**STAT 418: Introduction to Stochatic Processes and Probability for Engineering** (quite hard, but good course)

These are the foundational automation/control courses, e.g. the prerequisites for all other courses.

## MechE electives with a specialization on software tools and algorithms
**ME 444 - Engineering Optimization** - This course gives a well-rounded approach to optimization, both from a perspective of different algorithms/algorithm development and implementation/reasoning behind the use of optimization with regards to engineering projects. This course utilizes MATLAB (though other languages are acceptable) to approach optimization and related assignments. A few other prominent aspects of this course include a strong emphasis on independent/small group work as well as problem framing, restating/approaching problems in such a way that optimization is useful. 

**ME 497 - Machine Learning in Engineering** - This course gives an introduction to a wide variety of ML/AI topics such as neural networks, deep learning, and decision trees. There is a focus on the utilization of ML/AI tools as opposed to the development side, much of the assignments revolve around a discussion of use cases for ML approaches and associated reasoning. This course does not go into too much depth on any one particular topic but gives a good introduction to the field of ML/AI and covers a lot of topics that seldom covered in MechE courses.

**STAT 401** - This course essentially serves as an introduction to stats. R is used throughout to apply statistical concepts to data sets and study the results, though no previous understanding or use of R is required. The decision to take this course may sounds paradoxical: I would not recommend the course itself but having completed the course may prove to be a good decision. To expand, the course itself is really quite bland and is representative of something you would find in AP stats or even in the stats portion of ME348. That being said, this course is something of an entry-point to stats and can be useful if there is an intention to complete other stats courses or grad work in the future.

**MATH/CMPSC 451** - This course essentially covers different algorithms and approaches in relation to topics such as numerical integration, linear systems, and error analysis. This course requires a pretty thorough understanding of MATLAB as much of the work involves coding and use of the algorithms discussed in class. This course also had a pretty strong emphasis on validation and comparison between different algorithms that are applied to similar problem spaces. This would be a great course to take if interested in learning more about general programming, efficient programming, and algorithms.
**Feel free to email dzf5248@psu.edu with any additional questions regarding experiences in these courses**



## For MS-degree only
**ME 455 - Feedback Control**
**ME 481 - Computational Machine Dynamics** - see notes above
**ME 555 - Linear control** (you must have ME 455 first though).

MATH requirement options:
**ME 597 - Engineering Mathematics** - Prof Kontz does a great job teaching this
**STAT 418: Introduction to Stochatic Processes and Probability for Engineering** (quite hard, but good course)

## For PhD

Specializing in Control
### AERSP 565 System Identification taught by Professor Puneet Singla 
Synopsis:
This course introduces the theory of system identification and state-of-the-art computation methods for system identification. The theory of system identification deals with the subject of identifying or improving existing models of a physical system from input-output data and hence it is a culmination of system and control theory, optimization, linear algebra, calculus and probability theory. The student will get exposed to key intricate connections between different topics to learn basics of system identification theory which will provide them a platform to conduct research in this area and therefore produce creative scholarly products. The proposed 565 number groups it with related courses.

Recommended Preparations:
Consistent with coursework in undergraduate engineering programs, proficiency is required with linear algebra, complex numbers and control theory. In addition, proficiency with a scientific programming language (e.g., MatLab, Python) is expected.

Abbreviated Title:	System Identification
Effective Semester:	SP 2021

Course Outline via a brief outline or overview of the course content:
This course forms an introduction to the theory of system identification. The theory of system identification deals with the subject of identifying or improving existing models of a physical system from experimental/numerical data. While some physical systems are inherently difficult to model, others yield complex models that pose challenges when used for system analysis, design and real- time control system. In such problems, system identification is an invaluable tool to produce full or reduced order models for use by the system analysts/designer. This class will cover both the theory and computational methods to identify linear as well as nonlinear dynamical models from given input-output data. The reliability and limitations of various methods discussed will be assessed by considering various academic and engineering problems. Students will apply the learned method to the engineering applications through class projects and homework to build insight into methods covered in the class.

A listing of the major topics to be covered with an approximate length of time allotted for their discussion:
Mathematical Background (3 hours): Linear algebra fundamentals, System theory fundamentals, Least squares estimation, Maximum likelihood estimator.

Frequency Domain Methods (9 hours): Frequency Response Functions, Discrete Fourier Transform and the Fast Fourier Transform (FFT) algorithm, Analysis, Measurement and
Experiment Design.

Models for Identification (6 hours): Time domain models and various representations.

Subspace Methods (15 hours): Eigensystem Realization Algorithm (ERA), Observer/Kalman Filter Identification (OKID), Q Markov COVER Theory, time varying extensions of ERA and OKID

Rapprochement with Time Domain Methods (3 hours): Frequency Domain State Space Identification.

Advanced Topics (9 hours): Total least squares, l1 regularization, nonlinear system identification

Course Description:
This course will cover topics related to identifying frequency response function as well as linear state space models from input-output data. Topics include continuous and discrete time models, frequency response functions, model structure & parameterization, non-parametric models, subspace methods, observability & identifiability, model order estimation, sparse approximation and relationship to maximum likelihood estimation & Kalman filtering.

The name(s) of the faculty member(s) responsible for the development of the course:
Name: Puneet Singla (pxs433)

Instructional, Educational, and Course Objectives:
This section should define what the student is expected to learn and what skills the student will develop.
Upon successful completion of this course, students will be able to:
1. Use experimental input output data and estimate the best dynamic system models for linear systems.
2. Gain experience with several dynamic system models for regression (e.g., ARMA, ARX, ARMAX, bilinear and discrete-bilinear)
3. Gain exposure to key aspects of system theory such as controllability, observability, identifiability and persistence of excitation.
4. Gain experience of modal analysis and its relationship with input output data.
5. Gain insight into the inextricable connections between tools for reduced order modeling and system identification.

Evaluation Methods:
Include a statement that explains how the achievement of the educational objective identified above will be assessed. The procedures for determining students' grades should be specifically identified.
Students will be evaluated on the basis of Homeworks (15%), Mid-Term Exam (20%), Two Projects (20% each), Final exam (25%)

### IE 597 Special Topics section 005: Human Factors in Transportation Safety
Offered to graduate students in the Spring semester 2022, MW from 4 to 5 pm. A good course for studying human/AV interaction.

This course is designed to provide graduate students with the knowledge of different methodologies in human factors and the concepts and theories of human factors research in transportation safety. This course will cover the methods appropriate for studying humans, vehicles, and their interaction. It is designed to prepare graduate students with the knowledge of key topics in driver behavior research, including driver cognition and behavior, vehicle technology, driving impairment, elderly drivers and driving aggressiveness, driver performance modeling, and other road users. By the end of the class, the student will be able to formulate a research hypothesis, identify appropriate research method, and apply the knowledge gained in the course to conduct research in transportation safety domain. 

Course Information

Instructor: Dr. Yiqi Zhang

Description and Objective 

Human  Factors  in  Transportation  Safety is  composed  of  a  systematic  introduction  of  major concepts, theories and methods of human factors research in transportation safety. This course will cover the methods appropriate for studying humans, vehicles, and their interaction. It is designed to prepare graduate students with the knowledge of key topics in driving research, including driver cognition  and  behavior,  vehicle  technology,  driving  impairment,  individual  difference,  driver performance modeling,  and  other  road  users. By  the  end  of  the  class,  students  will  get  familiar with the cognitive capabilities and limitations of human drivers in transportation systems. Students will be able to formulate a research hypothesis, identify appropriate research methods, and apply the  methods  and  theories  learned  during  the  semester  toward  the  development  of  a  research proposal in the transportation safety domain.

Format 

This is a graduate seminar and therefore strongly favors group discussion based on a set of readings for  the  week.  Although  primarily  discussion  based,  there  may  also  be  instances  of  lectures, activities,  videos,  and  guest  speakers.  All  students  enrolled  in  the  course  are  members  of  our learning  community  and  are  required  to  be  full  participants  in  the  seminar.  This  includes completing required readings and assignments on time, participating in the discussion on a regular basis, leading class discussion when appropriate, and monitoring your own contributions so as to not be dominant

Required Reading Material

Shinar,  D.  (2017). Traffic  safety  and  human  behavior:  Second  edition.Emerald  Publishing Limited.(The ebook is available in the Penn State library, http://ezaccess.libraries.psu.edu/login?url=http://search.ebscohost.com/login.aspx?direct=true&db=nlebk&AN=1423752&site=ehost-live&scope=site

Recommended Reading Material

1.Wickens,  C.  D.,  Hollands,  J.  G.,  Banbury,  S.,  &  Parasuraman,  R.  (2015). Engineering psychology & human performance. Psychology Press.

2.Walker,  G.  H.,  Stanton,  N.  A,  &  Salmon,  P.M. (2015). Human  factors  in  automotive engineering and technology. CRC Press.

3.Sullman, M.,& Dorn, L. (Eds.). (2012). Advances in traffic psychology. Ashgate Publishing, Ltd.

Note: You have access to Walker’s and Dorn’s books online through the library’s website.Other reading materials will be uploaded later on Canvas.


### AERSP 566: Applied Optimal Estimation taught by Profs. Puneet Singla and Jacob "Jack" Langelaan
Justification of Course Number:
This course introduces theory and methods suitable for nonlinear estimation and filtering in aerospace problems such as system identification, navigation, and attitude determination. This includes estimating system states and/or parameters by fusing the mathematical model of the system with sensor observations. It is a culmination of dynamical systems, probability, information theory, optimization, linear algebra, and calculus. The student will be exposed to key connections between different topics in learning estimation theory and its application to guidance and navigation of aerospace vehicles. An understanding of estimation theory and exposure to the practical applications will provide students a platform to conduct research in this area and therefore produce creative scholarly products. The proposed 566 number groups it with related courses in dynamics and control.

A brief outline or overview of the course content:
The emphasis of this course is on an understanding of the stochastic processes and practical applications of related theory and methods in estimation and navigation. This will include an appreciation for the strengths and limitations of state-of-the-art numerical techniques for nonlinear filtering and control problems, and to learn to utilize stochastic system analysis methods as research tools. The reliability and limitations of various methods discussed will be assessed by considering various academic and engineering problems. Students will apply the learned method to the engineering applications through class projects and homework to build insight into methods covered in the class.

A listing of the major topics to be covered with an approximate length of time allotted for their discussion:
Deterministic State Estimation (6 hours): Problem Formulation, Dynamical Systems, State Observer Design, Least Squares, Sequential Least squares
Review of Probability Concepts (6 hours): Probability Theory, Conditional Probabilities, Bayes’ Rule, Expectation Integrals, Entropy, Fisher Information
Parameter Estimation (9 hours): Maximum Likelihood, Total Least Square, Maximum A-Posteriori, Minimum Variance, Cramer-Rao Bound
Dynamical Systems (6 hours): Markov Processes, White Noise, Chapman-Kolmogorov Equation, Linear Stochastic Processes, Statistical Linearization
Multi-Dimension Expectation Integrals (9 hours): Random Sampling, unscented Transformation, Quadrature Methods
Nonlinear Filtering Theory (9 hours): Extended Kalman Filter, Unscented Kalman Filter, Quadrature based Filters, Particle Filter, Multiple Model Adaptive Estimation.

Course Description:
This course would cover topics from basic linear and nonlinear stochastic processes to well-known Kalman filtering methods to recently developed nonlinear estimation methods at a level of detail compatible with the design and implementation of modern control and estimation of dynamical systems. These diverse topics will be covered in an integrated fashion, using a framework derived from stochastic processes, estimation, control, and approximation theory.

Course Justification
Instructional, Educational, and Course Objectives:
This section should define what the student is expected to learn and what skills the student will develop.
At the end of this course, students will be able to:
1. Understand and use the concept of stochastic processes to model engineering systems.
2. Learn batch and sequential strategies for parameter and state estimation.
3. Learn to apply linear filtering and control techniques to engineering problems.
4. Understand and derive numerical solution techniques to solve nonlinear filtering and control problems.
5. Get exposed to implementation issues such as computational complexity, reduction of filter dimension, colored noise, discretization etc.

Evaluation Methods:
Include a statement that explains how the achievement of the educational objective identified above will be assessed. The procedures for determining students' grades should be specifically identified.
Students will be evaluated on the basis of Home-works (15%), Mid-Term Exam (20%), Two Projects (20% each), Quizzes (20%)

### ME 597 "Materials that Compute, Learn, and Decide" (first offering would be ~ 2021 or 2022) by Prof. Joseph Najem
“Materials that Compute, Learn, and Decide.” 

The objectives of this course will be to: 

1) Introduce students to the synaptic and neural mechanisms underlying sensing, processing, and learning in the brain at exceptional energy efficiency.

2) Discuss how mechanisms can inspire a new generation of smart materials that can detect and process environmental stimuli and make decisions by adapting their physical properties.

3) Present a synergistic approach to study and develop brain-like materials by combining in situ characterization techniques and a mathematical framework for analysis and modeling. 

Topics will include: synaptic plasticity and learning, Hodgkin-Huxley equations, models of neural circuits, biology of learning, smart materials, signal processing, modeling dynamic systems, nonlinear dynamical materials and systems, oscillation in mechanical and electrical systems, chaos, and more. These topics are relevant to the proposed research of creating brain-like materials. Numerous examples and problems will directly relate to the various aspects of memory, learning, and computing in materials. 

### AI and ML courses
IE330: Engineering Analytics (Basic ML Course) - started around 2006

IE562: Smart SYstems Design (AI Course) ( I use Russell & Norwig, and Pearl as main references) - started as ES in IE and Manufacturing around 1987, now morphed into a solid AI course. IE562 was almost among the first 3 or 4 AI courses on campus (Tony Maida in CS was teaching a logic-based AI course, Ian Parberry in CS was teaching a NN course, and Late Professor Bose was teaching a theoretical NN course). 

IE582: Advanced Engineering Analytics (ML Course). - Started around 2011.


<a href="#odds-and-ends">Back to top</a>


# Collaborators at Penn State 

A list of faculty at Penn State that you may not know of into automation. This is useful for PhD students looking for committee members!

[Prof. Long He, Assistant Professor of Agricultural and Biological Engineering](https://abe.psu.edu/directory/luh378)  Specializes in Robotics and Automation for Specialty Crops

[Prof. Vasant Honavar, Professor and Edward Frymoyer Chair of Information Sciences and Technology](https://ist.psu.edu/directory/vuh14) Specializes in AI and machine learning, knowledge representation, data science, and applied informatics.

[Prof. John Messner, Charles and Elinor Matts Professor of Architectural Engineering](https://www.ae.psu.edu/department/directory-detail-g.aspx?q=JIM101) Specializes in automated and robotic construction systems, advanced visualizations, human-machine and virtual reality building information systems.

[Prof. Yanxi Liu, Professor of Computer Science and Engineering and Electrical Engineering](http://www.cse.psu.edu/~yul11/) Specializes in motion capture systems for smart health, perception action and cognition, and humanoid robotic simulations

[Prof. Scarlett Miller, Associate Professor in the School of Engineering Design, Technology and Professional Programs (SEDTAPP)](https://www.engr.psu.edu/britelab/people.html) Specializes human-system interactions within the design process, particulary the early phases of design, and how to develop innovative consumer products using user-centered design techniques.

<a href="#odds-and-ends">Back to top</a>

### Stat courses
ENGR 820, Applied Engineering Research Methods - This research methods course focuses on the development of competencies required to become a successful professional researcher in engineering fields. While other courses will focus on an engineering topic and provide some insights into the associated research methods, this course aims to provide an overview of research methods used throughout engineering disciplines and provide guidance for when and why different methods should be employed in professional research practice. Students should come into the class with a research area defined and the class will provide students with a framework to conduct their own research through a pilot study and, thereby applying these methods to their professional practice. Course topics include: research ethics, literature review, problem framing, experimental design, qualitative and quantitative data analysis, and data presentation in professional engineering research fields. These topics are central to conducting effective engineering research. Students that complete this course will be able to: Define ethical requirements for application in engineering research; Critique and review literature to identify gaps for future work; Design and implement an experiment; Analyze and defend qualitative and quantitative results; Write and structure effective research papers; And report and defend research decisions and conclusions. Overall the objective of this course is to provide students with the tools to conduct research experiments and defend results in order to prepare them for research at the graduate level.

STAT 500, Applied Statistics - Descriptive statistics, hypothesis testing, power, estimation, confidence intervals, regression, one‐ and 2‐way ANOVA, Chi‐square tests, diagnostics.

STAT 501, Regression methods - Analysis of research data through simple and multiple regression and correlation; polynomial models; indicator variables; step‐wise, piece‐wise, and logistic regression. 

STAT 502, Analysis of Variance and Design of Experiments - Analysis of variance and design concepts; factorial, nested, and unbalanced data; ANCOVA; blocked, Latin square, split‐plot, repeated measures designs.

STAT 503, Design of Experiments - Design principles; optimality; confounding in split‐plot, repeated measures, fractional factorial, response surface, and balanced/partially balanced incomplete block designs. 

STAT 506, Samping Theory & Methods - Theory and application of sampling from finite populations. 


# Committees and Service

<!-- COMMITTEES AND SERVICE -->
<details closed> 
  <summary> Click to see/unsee </summary>
  <ul>
    <li>
      <a href="https://sites.google.com/site/trbvehiclehighwayautomation/Home?utm_medium=email&utm_source=govdelivery">
      The Transportation Research Board of the National Academies, TRB-ACP30 "Vehicle Highway Automation" committee  
      </a>
      This committee is concerned with the development, application, and operation of driver assistance and automated 
      control to the vehicle and highway system. The scope includes all forms and levels of control ranging from driver 
      assistance systems operating on existing streets and highways to full vehicle control systems operating on freeway 
      type and/or dedicated lane facilities. It further includes systems that support specialized highway-related functions 
      including maintenance, fleet operations, and similar applications. The emphasis is on control systems that will enhance 
      user safety, system efficiency, and operational performance while providing for increased convenience and trip quality 
      to the highway user. The objectives of the committee are to provide a focus and forum within the TRB for vehicle-highway 
      automation and to promote a better understanding within the transportation profession of these systems including their 
      research, deployment, and operation.
      <br>   
    </li>
    <li>
      <a href="https://www.transportation.gov/utc/highly-automated-systems-safety-center-excellence">
      US DOT's "Highly Automated Systems Safety Center of Excellence"
      </a>
       Goal: to have a Department of Transportation workforce capable of reviewing, assessing, and validating the safety of automated technologies.
       <br> 
       The Highly Automated Systems Safety Center of Excellence shall—
       <br> 
       (a) serve as a central location within the Department of Transportation for expertise in automation and human factors, computer science, data analytics, machine learning, sensors, and other technologies involving automated systems;
       <br> 
       (b) collaborate with and provide support on highly automated systems to all Operating Administrations of the Department of Transportation; and
       <br> 
       (c) have a workforce composed of Department of Transportation employees, including direct hires or detailees from Operating Administrations of the Department of Transportation and other Federal agencies.
      <br>
    </li>
  </ul>

</details>

<a href="#odds-and-ends">Back to top</a>


# Fun Stuff

<!-- FUN STUFF CODES -->
<details closed> 
  <summary> Click to see/unsee </summary>
  <ul>
    <li>
      <a href="https://www.youtube.com/watch?v=9vJRopau0g0&ab_channel=TEDxTalks">
      TED talk: it's not a bug, it's a feature
      </a>
      <br>    
    </li>
    <li>
      <a href="https://github.com/ivsg-psu/Errata_FunStuff_NYTimesSpellingBeeSolver">
      Errata_FunStuff_NYTimesSpellingBeeSolver
      </a>
      <br>   
      A MATLAB code that solves the New York Times spelling bee (for when people are driven mad by not finding the very last word)
    </li>
  </ul>
</details>

<a href="#odds-and-ends">Back to top</a>

