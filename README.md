# Lego Robot Project
This project was part of our Robotics and Mechatronics project course. The goal was to build a robot that can flip a cube based on the assigned color and then score a goal in the designated area. The final robot was first put through a demo round to check its function and then competed against other robots in a tournament fashion to analyze its effectiveness.
## Design
The front of the robot with the flipping mechanism had a container with two arms at the side with sliding parts which allowed the cube to be slid into place. The front bumpers were bent in a way to always register input keeping rotation in mind.

![](https://raw.githubusercontent.com/baigsterinator9000/Lego-Robot-Project-Sem-2-/master/RobotPics/20161110_133350.jpg)

The light dependent resistor (LDR) was placed at the front to detect the goal area with the light.

![](https://raw.githubusercontent.com/baigsterinator9000/Lego-Robot-Project-Sem-2-/master/RobotPics/20161110_133417.jpg)

With two main wheels was a slider joint to balance the robot weight. Another infrared radiation sensor (IR) was placed on the bottom of the right arm to detect black and white lines.

![](https://raw.githubusercontent.com/baigsterinator9000/Lego-Robot-Project-Sem-2-/master/RobotPics/20161116_161456.jpg)

A servo motor attached with an arm and two wheels served as the flipping mechanism. The light gate placed between the arms of (IR sensors) helps detect the cube.

![](https://raw.githubusercontent.com/baigsterinator9000/Lego-Robot-Project-Sem-2-/master/RobotPics/20161116_161520.jpg)

Other supporting parts were added to properly align the cube for flipping and the whole structure was reinforced with rubber bands and cable ties to prevent breakage during the competition.

![](https://raw.githubusercontent.com/baigsterinator9000/Lego-Robot-Project-Sem-2-/master/RobotPics/20161116_161923.jpg)

Combining the features above resulted in a solid and functional design for the robot to compete in the tournament.

![](https://raw.githubusercontent.com/baigsterinator9000/Lego-Robot-Project-Sem-2-/master/RobotPics/20161116_162326.jpg)
## Code workflow
The code included in this repo was created according to the requirements and the workflow was as follows.

![Flowchart of the workflow](https://raw.githubusercontent.com/baigsterinator9000/Lego-Robot-Project-Sem-2-/master/RobotFlowchart.PNG)

## Results
This project was a success as the robot built qualified into the tournament and managed to score second place among 17 other robots. A demo video is of the robot is below.
### The Arena
This is the arena where the competition took place

![The Arena](https://raw.githubusercontent.com/baigsterinator9000/Lego-Robot-Project-Sem-2-/master/RobotPics/20161110_104856.jpg)
### Flipping
![Flipping](https://media.giphy.com/media/Rkz7CSL0Fwb3b52Hsw/giphy.gif)
### Scoring
![Scoring](https://media.giphy.com/media/j2wwjvLaAL2lKZCRwO/giphy.gif)
### Navigating
![Bumping](https://media.giphy.com/media/Xbt9LaEvGuSDxQpNLn/giphy.gif)

Full video here >> [Lego Robot Tournament](https://www.youtube.com/watch?v=luLTKh0Fiyc)
