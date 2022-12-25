# Tony Hawk Skate Simulator

## Context

This program was developed as an integrative project for the final course (420-204-RE) of the Computer Science & Mathematics collegial program.

## Program description

The program consists of a skater that is released down an incline with variables such as the mass,
gravity, slope of the incline, and friction that will change the various energies (kinetic and potential energy) of the skater as it follows its path. Hence, we used concepts mostly related to
the mechanic’s course. The main physics concepts used are forces such as friction and gravity,
and kinematics concepts like speed and acceleration. To display the difference in gravity, many
planets are available to switch to.

![Image: GUI of TonyHawkSkateSimulator](https://drive.google.com/uc?export=view&id=16EJoFRg-byruXqES6SnnaP_LYxcc2bCb)
*Figure 1: The program in a working state, with the skater falling down the plane*

The user inputs a double for the mass, can modify the angle of the incline, the friction
coefficient, and can change the planet, to change the gravitational acceleration, using a combo
box. Furthermore, the user can play, pause and reset the animation, as well as to slow it down.
The user can change the planet the skater is in like earth, the Moon, and Mars.

## Technologies and frameworks used

This program is written in **Java** and uses...

### Frameworks used

* The JavaFX GUI framework
    * The GUI designed using FXML
* The Maven build automation tool

## Developement kits used

The current JDK is Azul Zulu OpenJDK version 15.0.9

## Contributers:
* Mehdi Benouhoud
* Réda Alidrissi-Omari
* David Qi
* Changfan Deng

## Task repartitions

### Réda:
* Design of the assets 
* CSS implementation
* Changing between planets 
* About window

### Mehdi:
* Regular calculation of position, velocity, and acceleration for each frame
* Input of the skater’s mass
* Play, pause, and reset the animation
* Animation of the skater riding down the plane
* Change the plane angle
* Energy graph 
### Changfan:
* Import of other planets’ gravity constants
* Slow motion
* Change between different planets and their gravity constants
### David:
* Input of the dynamic friction coefficient
* Animation of the skater riding down the plane
* Change the plane angle
* Animation of the parabola

# Challenges

## Working under a time constraint

It was challenging for our team to deliver a complete and complex project in a restraint time span. We did projects and assignments earlier in our CEGEP curriculum, but this was the first time that we had to develop a project of similar scale. Indeed, this increased the impacts of even the smallest errors or delays. 

## Adapting to unknown Java technologies and components

Although we had virtually comprehensive comprehension of the technologies available with the JavaFX framework due to the three previous courses of programing at Vanier, being a programmer is an everlasting learning journey. Indeed, there were several elements that we didn’t study in class. It was challenging for us to grasp certain elements

## Learning CSS 

For the CSS, one of the challenges faced was to figure out how to customize the project in the first place, since the base CSS styling does not allow to have pixelated visuals. Therefore, the easiest and freest way we decided to choose was to make background images for each component of the project to make it look like the background image is the actual component. For example, we created background images for the buttons, wrote CSS code to make the buttons transparent and put the background image that is of the same size instead. Learning CSS was a bit hard because we did not cover it a lot of last semester, and because there is not a lot of info on its implementation with Java FX in specific situations.

## Issues

It is buggy and some temmates didn't do their tasks properly






