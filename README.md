# Robo-Racer bot

The Robo Race bot, created by students of the RoboTech Club at the National Institute of Science Education and Research, was built to participate in techfest competitions. The project aimed to enhance understanding of DPDT switches, AC to DC converters for maintaining 12V in the circuit, and the functioning of a wired car instead of a wireless one.

# Time Line

- Start of Project - 14 January 2025
- Participation in NIRMAN 4th Edition in Silicon Institute of Technology, Bhubaneswar - 6 February 2025

# Race Track : Rules and Scoring

The race track will feature various obstacles and surprise elements, each requiring the bot to complete a specific task. If the bot successfully completes a task, full points are awarded; if not, no points are given. Teams may skip obstacles, but doing so incurs a point deduction. Additionally, if a team touches their bot to reposition it on the track, a time penalty is applied. Two bots will compete simultaneously, and their completion times will be recorded. The bot that finishes the track in the shortest time wins the competition.

# Conceptual Framework for Wired Bot Control 

The bot is designed to operate using two DPDT switches for control and a wired connection for navigation. It utilizes an AC power supply, which is converted to DC using an AC-to-DC converter to ensure maximum efficiency for the motors.

# Equipments Used

- 10 m long Copper Wire
- AC-DC Converter
- Acylic Used to make Chassis
- Cardbord Box for placing the switch
- DPDT Switches ×2
- Glue gun, Soldering iron, Double Tapes and Tapes
- Motor Wheels ×4
- TT Motors ×4
- Waterproof Tape

# System Architecture

At the beginning, the bot is equipped with two front motors and two rear motors. The two left motors are connected to one switch, while the two right motors are connected to another. The chassis is fully enclosed, with a single exit point for all wiring. These wires lead to the control box, where two DPDT switches are connected to the bot before finally linking to the AC-DC converter.


# Mechanical Design

The 2D design is created in Onshape, and a laser cutter is used to produce a precise acrylic design. Double-sided tape secures the motors, and a glue gun is used for additional stability. All wiring is firmly attached to the base of the acrylic with double-sided tape. The bot is then fully enclosed in acrylic, secured with a glue gun, and finally wrapped in waterproof tape to protect the wiring and connections during the race.

[The Link for the 2D design](https://cad.onshape.com/documents/d82813d081fd772694425e77/w/5dc70dbbabd8a3c58374bf99/e/4a447ad0531e1195e50dc866)

# Electrical Connections and Steering

The connections to the bot is given below :

![Image](https://github.com/user-attachments/assets/f3ca6ceb-cd8a-4a80-ba53-ce908aebaecd)

The diagram of DPDT switch is given below :

![Image](https://github.com/user-attachments/assets/69a5833c-b81a-4d7a-b036-65f34ae489ef)

**<ins>Steering</ins>**
- The two left motors and two right motors are connected to separate switches, allowing independent control of each side.
- The DPDT (Double Pole Double Throw) switch has three states: ON, OFF, and ON. The key difference between the two ON states is the polarity, which is reversed between them.
- This switching function enables the bot to steer left and right.
- To move forward, both switches are set to the ON position with forward polarity.
- To turn right, the left switch is turned OFF while the right switch remains ON (forward polarity). Similarly, to turn left, the right switch is turned OFF while the left switch remains ON (forward polarity).
- To move backward, both switches are set to the ON position with backward polarity.
- To rotate in place (circular motion), both switches are turned ON but with opposite polarities.

# Performance Evaluation

- The bot works good in plane surface and is very easy to control and very responsive to user's command
- After some time the wheels becomes loose 
- The Motor directions were not correct and motors were not firm in their position
- The bot had difficulty in climbing slopes
- The wires used in the bot at times came  under the wheels causing it to stop
- The bot has very high speed
- After some time of running ,the wires may becmoe loose which may lead to loose connections and thereby sudden stoppage of the bot

# Future Improvements

There are many inprovements to be done in the bot
- Using good equipments for building bot.(Having a steel body)
- Using caterpillar tyres
- Usage of bigger motors and wheels of bigger diameters
- Usage of wireless bot by connecting the motor driver with the flysky
- Making large number of test runs before  the final run
- Ensuring that the connections reamin intact in all the situations

# Conclusion

The project did not achieve complete success as expected, but it provided valuable learning experiences, particularly in working with a wired bot. However, due to implementation challenges, the project faced setbacks. By incorporating the necessary improvements in the future, the bot can become more robust and better suited for such tracks, ultimately increasing its chances of winning the competition.

# Members

- Dr. Subhankar Mishra (Faculty incharge of RoboTech Club) - Guidance for the Project
- Dadhichi Das (President of Robotech Club) - Mentor of Whole Project, Bug Fixing
- Girija Sankar Ray (Senior) - Mentor, Bug fixing
- Rikan Mahakur (Senior) - Mentor of Mechanical work
- Abhijeet Parida (Captain) - Wiring connections
- Soumalya Naskar - Designing for project
- Mayukh Mukherjee - Mechanical and Ciruciting work for project
- Promit Ghosh - Body Designing and Mechanical


