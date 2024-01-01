# Digital-Prototyping-Interactive-Prototype-2


Background information of the projects(Problem space): Most of us have experienced long distance driving, and we know long distance driving can drain your energy easily. The longer you drive, the more fatigue you can feel. Fatigue driving can affect a driver's concentration, which can lead to traffic accidents easily. Fatigue driving is a big issue for everyone, and we need to treat it seriously.To resolve this problem, developing a driver alert system is needed. The driver alert system needs to collect some input data. Afterwards, the system needs to process the input data and provide corresponding feedback to the driver. The system needs to analyze the data precisely, and provide the most suitable feedback that fits the driver’s current condition. The details of the feedback mechanisms are explained within the statement of delivery document. By having the driver alert system, drivers can stay awake and focus on the road when they drive, so that they can keep themself safe.



Introduction of the Interactive prototype projects: The background information above briefly explains the problem we want to solve and the potential solution. In the interactive prototype projects, the goal is not building the actual product and deploying the system to the public. The focus of the interactive prototype projects are treating the problem and the  solution mentioned above as the concept, and I need to explore the challenge/aspect within the concept afterwards. 

After the challenge/aspect is defined, the interactive prototype project will enter its second stage, which is the prototype development.

The prototype development has two parts, which are the hardware and the software. For the hardware, I used the Adafruit Circuit Playground as the physical component, which is used for the physical interaction between the system and the users. For the software, I used Unity to develop the software prototype. The hardware component will communicate with the software prototype constantly. The digital prototype is specifically designed for the challenge/aspect that we defined in the previous stage. Once the digital prototype development is completed, the testing session will begin.

The final stage is the testing session. In the testing session, I will explain the concept to my testers. Afterwards, they will perform some operations with the digital prototype. I will conduct various evaluations throughout the testing session, for instance observations and interviews. These evaluations can give me useful insights on the challenges/aspects that I defined in the earlier stage, so that I will have a clear direction in my future developments. 

The interactive prototype project has three digital prototypes. Each of these prototypes is corresponding to a specific challenge/aspect on the problem space we mentioned earlier.


The coding folder contains the Arduino codes and the Unity codes.

The statement of delivery contains the documentation of the digital prototype and the testing session information.

The ReadMe.md provides background information and explains the flows of the interactive prototype. In addition, it will have a detailed explanation on the target challenge/aspect, and its digital prototype.




Prototype2: In prototype 2, the research idea is “Does automated data collection system perform better than manual data input system in the driver alert system context?” Automated data collection system means the system will obtain the required information through hardware components and the predefined programs, so users don’t need to pay attention to the data collection procedures,since the system will take care of the data collection procedures. Manual data input system is the opposite of the automated data collection system, it requires users to enter input data to the system manually. 

In prototype 2, I utilize prototype 1’s design and redesign a prototype that can collect head movement data from the driver and provide corresponding feedback accordingly. The accelerometer feature is embedded on the Adafruit circuit playground. I tried to embed the circuit playground on a headband. When drivers lean their head forward, the accelerometer values will change based on the inclined angle. If the degree of the angle is less than the predefined value, the system will provide fierce feedback, since a small angle means the driver’s head is leaning forward so he is not focusing on the road. If the degree of the angle is larger than the predefined value, it is considered as normal, which means the driver's head position is facing forward so there are no symptoms the driver is falling asleep. When the alert is triggered, the circuit playground’s LED will turn red and it will also ring. In addition, the Unity screen will turn to red as well. Conversely, if it is in the normal mode, the LED light on the circuit playground is green and the circuit playground will not ring. Also, the Unity screen will remain green when it is in the normal mode.

Testers need to test the prototype 2 in the prototype 2 testing session. Testers need to work with the car simulation game. At the same time, they need to pretend they fall asleep by leaning their head forward occasionally. When the testers lean forward, the tester needs to remember if it triggers the alert system.

Observations will be performed while the testers are testing the prototype. Once the testers completed all the testings on the prototype, the interview session will begin. After having a detailed observation and interviews, I realize most testers believe the automated data collection system is a better approach than the manual data input approach, since most testers think it is more efficient. But the testers also pointed out there are drawbacks in the current system, for instance, false detection and insensitivity of the system. These drawbacks can impact user experience heavily, so I can work on these aspects in the future developments. In future developments, I can work on different accelerometer values and find out which will provide the most satisfactory result. Also, I may add a confirmation system to the system and trigger it when it is needed. These useful insights can help me to find a proper solution to the challenge that I raised earlier, so I can have a clear direction for the future improvements.

Detailed information of prototype 2,background information , testing session, and key takeaways can be found in the statement of delivery. 

The following link shows the prototype 2 video, which demonstrates how interactive prototype 2 works. Link:   
