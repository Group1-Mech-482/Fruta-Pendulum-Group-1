# Furuta-Pendulum-Group-1
# California State University, Chico 

Team Members: Ryan Calbert, Jarrel Cook, Michelle Gomez, Noah McCracken, Miguel Rodriguez 
<br/>
MECA 482: Fall 2021
<br/>
### Table of Contents:
1. Introduction 
2. System Requirements
3. Controller and Design and Simulations 
4. Model
5. Results

Presentation video click here.

### Introduction 

   In 2020 people worldwide were forced to remain inside, threatened by a global pandemic. With much more time on their hands, many turned to adapt pets to keep them company and busy. As a result of many new pet owners, pet toys and accessories are increasingly in demand. This page will review a prototype of an interactive cat toy. The toy's main component will be an inverted rotary pendulum, also known as a Furuta pendulum. The pendulum will react to a displacement caused by the animal, which allows for minimal human interaction. Along with the pendulum, the toy will have shielding to protect the animal and a textured ball to stimulate the cat's natural prey drive.

   A Furuta Pendulum consists of three main components, an electric DC motor and an arm for which the third component, the pendulum, is connected. As the system is initialized, the DC reacts to the pendulum's position and produces torque. The torque creates rotation of the arm in a horizontal plane. The pendulum is connected to the arm but can rotate freely in a vertical plane, with the arm as its focal point. The furuta pendulum is able to rotate and balance the arm in an upright position. The vertical arm is able to correct itself if a small displacement is applied to it, such as a cat hitting it. This allows for the furuta pendulum to be a great interactive cat toy. 

### System Requirements

Capabilities Database 
</p>
<p align="center">
<img src="Capabilities Database.PNG" width="800"/>
</p>


Block Diagram 
<br/>


Logical/functional Viewpoint 
</p>
<p align="center">
<img src="logical.PNG" width="800"/>
</p>
<br/>

### Controller and Design Simulations 

### Model
<p align="center">
<img src="Physical Model of Furuta Pendulum.png" width="400"/>
</p>
   The main parameters of the diagram are as follows: 

* &theta;<sub>o</sub> is the angular position of the arm in radians.
* &theta;<sub>1</sub> is the angular position of the pendulum with respect to the pendulum in the downward position, in radians.
* &tau; is the torque coming from the electric motor.
* I<sub>o</sub> is the moment of inertia of the arm plus the motor inertia.
* L<sub>o</sub> is the length of the arm.
* m<sub>1</sub> is the pendulum mass.
* l<sub>1</sub> is the location of the center mass of the pendulum.
* J<sub>1</sub> is the moment of inertia.


### Results

### Appendix A: MATLAB Code

### References
