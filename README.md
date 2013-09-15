DSProject2_CarRacing
====================
This is the group assignment of COMP90015

Group Members: Tony, Simon, Tian, Josh

Target: Create an on-line car racing game using TCP&RMI technology.
========================================
Phase I: Design your car
Using a tool such as xpaint, your team should create a GIF image of a race car viewed from the top (suggested size: 50X50 pixel). You should create 16 versions of the image rotated around its center, i. e., one for every 22.5 degrees around the circle 
You will need two racing cars with the same 16 views. Make sure you can distinguish the two cars. Be creative in the design of your cars! 
Write a Java application that spins your two cars. You can see my solution by running: 
java Spin 50  (here 50 is the time in milliseconds for the animation delay)

Phase 2: Start the race track
Create a Java application for a race track where you can "drive" your two cars on one workstation 
To see the track, run the following: 
java Track 
Sample codes for making a track

Phase 3: Setup runtime environment
Select four keys for each of the two players
Two keys are used to change the direction of their car. A key press turns the car 22.5 degrees left or right. 
The other two keys are to change the speed of their car. The speed is an integer value from 0 to 100. One press of a key either increases the speed by 10 or decreases the speed by 10.
Write a Java application that allows two persons to drive their own cars around the racetrack. 
You may add additional graphical features to the track to make it visually more interesting. 
Your team should add collision detection between a car and the walls of the racetrack and between the two cars. 
In the event of a collision of a wall, the car crashes and its speed becomes 0. The other car can proceed. 
In the event that both cars collide, both cars crash and there is no winner. 
Add a Restart option as a menu item to allow the race to start over. 

Phase 4: Race cars on two workstations
The idea here is to have a server and two clients to allow each player to drive his or her race car on different computers. 
Design issues:
What functionally is performed on the server? Does the server need to interact with a database or legacy software? Does it provide centralized services? 
In this phase your team is to use as much of Phase 2 as possible. Therefore, the two clients perform most of the functionality. The server only provides the communication pipe between the two clients. 
What functionally is performed on the client? What user interface needs to be provided? 
A user can only control his or her own car with four keys. When one person drives his or her car, the motion of the car should appear on both workstation's screens. If the two cars collide, the game is over and both clients need to be notified. Allow either player to restart or exit the game from a menu. 
How many clients? And what categories of clients? 
In this phase we have two clients. 

========================================
Due time:
Phase 0: Team finalized – today OR by the next class (Sept 11). 
Phase 1 – Sept 25
Team should email the working Java code and a snap shot of the output. 
Phase 2 – Oct 9
Due: just discussion in the class on progress
Team should hand in a print of the working Java code and snap shots of the output. 
Phase 3 –  Oct 16
Due: discuss health of project
Team should email the working Java code and snap shots of the output. 
Phase 4: Execution and Project Closing – Oct 30
Your team should hand in a print of the working Java code and snap shots of the output.
A demonstration is required
A report should include:  system architecture, communication protocols, design diagrams, and a section on contribution of each member. 
Timely submission and progress/presentation in class: 4 marks (1 mark for each phase). 
