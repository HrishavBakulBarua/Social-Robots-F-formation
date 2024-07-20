# Enabling Social Robots to Perceive and Join Socially Interacting Groups using F-formation: A Comprehensive Overview [ACM Transactions on Human-Robot Interaction]


<p align="center">
    <img width="800" src="assets/Social_robot_f-formation.gif" alt="Material Bread logo">
    <br>
</p>

## About the project

This project is a collaboration between researchers from [TCS Research, Kolkata, India](https://www.tcs.com/what-we-do/research), [Monash University, Melbourne, Australia](https://www.monash.edu/), [Yale University, USA](https://www.yale.edu/), [University of Naples Federico II, Naples, Italy](https://www.international.unina.it/), and [University of Gottingen, Germany](https://www.uni-goettingen.de/en/1.html) 

Project Members - 

[Hrishav Bakul Barua](https://www.researchgate.net/profile/Hrishav-Barua) [(Monash University, Melbourne, Australia and TCS Research, Kolkata, India)](https://www.tcs.com/what-we-do/research),                                                                                                  
[Theint Haythi Mg](https://www.researchgate.net/profile/Theint-Mg) [University of Gottingen, Germany](https://www.uni-goettingen.de/en/1.html),                                                                                                                                                   
[Pradip Pramanick](https://www.linkedin.com/in/pradip-pramanick-804297115/?originalSubdomain=in) [University of Naples Federico II, Naples, Italy](https://www.international.unina.it/), and                                                                                                      
[Chayan Sarkar](https://www.linkedin.com/in/csarkar87/?originalSubdomain=in) [Yale University, USA](https://www.yale.edu/)      

### <ins>Funding details<ins>

This work is supported by the prestigious [`Global Excellence and Mobility Scholarship (GEMS)`](https://www.monash.edu.my/research/support-and-scholarships/gems-scholarship), Monash University. 


## Overview

Social robots in our daily surroundings, like personal guides, waiter robots, home helpers, assistive robots, telepresence/teleoperation robots etc., are increasing day by day. Their usability and acceptability largely depend on their explicit and implicit interaction capability with fellow human beings. As a result, social behavior is one of the most sought-after qualities that a robot can possess. However, there is no specific aspect and/or feature that defines socially acceptable behavior and it largely depends on the situation, application, and society. In this article, we investigate one such social behavior for collocated robots. Imagine a group of people is interacting with each other and we want to join the group. We as human beings do it in a socially acceptable manner, i.e., within the group, we do position ourselves in such a way that we can participate in the group activity without disturbing/obstructing anybody. To possess such a quality, first, a robot needs to determine the formation of the group and then determine a position for itself, which we humans do implicitly. There are many theories which study group formations and proxemics; one such theory is F-formation which could be utilized for this purpose. As the types of formations can be very diverse, detecting the social groups is not a trivial task. In this article, we provide a comprehensive survey of the existing work on social interaction and group detection using f-formation for robotics and other applications. We also put forward a novel holistic survey framework combining some of the possibly more important concerns and modules relevant to this problem. We define taxonomies based on methods, camera views, datasets, detection capabilities and scale, evaluation approaches, and application areas. We discuss certain open challenges and limitations in current literature along with possible future research directions based on this framework. 
In particular, we discuss the existing methods/techniques and their relative merits and demerits, applications, and provide a set of unsolved but relevant problems in this domain.

## Overview of F-formation and the social spaces 

<div>
    <img src="assets/F-formation.png" alt="Image 2" width="700" style="float:left; margin-right: 100px;" />
</div>

F-formation (facing formation) is defined as the set of patterns that are formed during social interactions of two or more people. A robot can join an existing group or go to a single person and form a new group. There are three social spaces related to f-formation, which are: O-space, P-space, and R-space. O-space is known as the joint transaction space which is the interaction space between participants. P-space is the space where active participants are standing. R-space is the area that surrounds the participants and is outside the interaction radius as shown in the above figure.

### Human proxemics 

Human proxemics is the study of how space is used between humans or how it is set between humans and others during interactions or performing an activity.The below figure shows the various specified distance ranges for different designated interaction types on the basis of intimacy level between the participating people. The distance ranges specified in green colored boxes are relevant to group/interaction and f-formation detection perspective. The blue-colored boxes signify distance ranges that are not generally seen in any f-formation.

<div>
    <img src="assets/Human_Proximics.png" alt="Image 2" width="700" style="float:left; margin-right: 100px;" />
</div>


## Uniqueness if this work

<div>
    <img src="assets/Compare.png" alt="Image 2" width="1000" style="float:left; margin-right: 100px;" />
</div>

## Comprehensive list of f-formations which are/can be used for group and interaction detection tasks in vision and robotics

<div>
    <img src="assets/List_formations.png" alt="Image 2" width="1000" style="float:left; margin-right: 100px;" />
</div>

##  Comprehensive list of f-formations and their corresponding changed formations after a person/robot joins it. Also, the relevant possible trajectories a robot/person should take in each of the case

<div>
    <img src="assets/List_joining.png" alt="Image 2" width="1000" style="float:left; margin-right: 100px;" />
</div>

The table below lists the comprehensive list of formations before and after a robot/human has joined. The “*” signifies that the number is the minimum
requirement for that particular formation.

<div>
    <img src="assets/Joining_tab.png" alt="Image 2" width="1000" style="float:left; margin-right: 100px;" />
</div>


