EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

AIM:

To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

SCENARIO:

You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

1.Accuracy

2.Coherence

3.Simplicity

4.Speed

5.User experience

OUTPUT:
Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

ZERO SHORT PROMPTS:


PROMPT:WRITE A WELL STRUCTURED, BEGINNER FRIENDLY ARTICLE ON THE BASICS OF CLOUD COMPUTNG FOR 200 WORDS

Basics of Cloud Computing: A Beginner’s Guide
Cloud computing is the delivery of computing services—including servers, storage, databases, and software—over the internet ("the cloud"). Instead of buying, owning, and maintaining physical data centers and servers, you rent access to these resources on an as-needed basis from a provider like Amazon Web Services (AWS), Microsoft Azure, or Google Cloud.
How It Works
Think of the cloud like your home electricity. Rather than maintaining your own generator (local server), you plug into a utility grid (cloud provider) and pay only for what you use.
Key Service Models (IaaS, PaaS, SaaS)
Cloud services are generally divided into three main types:
Infrastructure as a Service (IaaS): Renting raw infrastructure like virtual machines and storage.
Platform as a Service (PaaS): Providing a platform for developers to build and deploy applications without managing the underlying hardware.
Software as a Service (SaaS): Delivering complete software applications over the internet, such as Google Workspace or Dropbox.
Why Move to the Cloud?
1.Cost-Effective: Eliminates the high cost of buying hardware; you pay only for what you consume.
2.Scalability: Instantly increase or decrease resources based on demand.
3.Accessibility: Access your data and applications from anywhere with an internet connection.
4.Reliability: Cloud providers offer data backup and disaster recovery services
CHATGPT:
Basics of Cloud Computing
Cloud computing is a technology that allows users to store, manage, and process data over the internet instead of using a personal computer or local server. In simple terms, it means accessing computing services such as storage, software, and processing power through the internet, often called “the cloud.”
One of the main advantages of cloud computing is accessibility. Users can access their files and applications from anywhere using any device connected to the internet. For example, services like online document editors or photo storage platforms allow users to work and save files without installing software on their computers.
Cloud computing also provides cost efficiency. Instead of buying expensive hardware and maintaining servers, businesses and individuals can pay only for the services they use. This makes it easier for startups and small companies to use advanced technology without large investments.
There are three main types of cloud services. Infrastructure as a Service (IaaS) provides basic computing resources like virtual machines and storage. Platform as a Service (PaaS) offers a platform where developers can build and deploy applications. Software as a Service (SaaS) delivers software applications through the internet.
In conclusion, cloud computing has become an essential part of modern technology. It helps individuals and organizations store data, run applications, and collaborate efficiently while reducing costs and improving flexibility.
GEMINI:
Demystifying the Cloud: A Beginner’s Guide
Imagine you stopped buying DVDs and started using Netflix. That is the cloud in action. Simply put, cloud computing is the delivery of computing services—including servers, storage, databases, and software—over the internet ("the cloud").

How It Works
Instead of owning and maintaining physical hard drives or bulky servers under your desk, you access technology resources hosted in massive data centers by providers like Amazon (AWS), Microsoft, or Google. It’s like switching from a personal well to a city water utility: you turn on the tap, use what you need, and pay only for that amount.
The "Big Three" Service Models
To keep things simple, the cloud is usually divided into three categories:
Infrastructure (IaaS): Think of this as renting the "raw land." You get the basic building blocks (servers and storage) and build whatever you want.
Platform (PaaS): This is like renting a "pre-built workshop." It’s designed for developers to build and host apps without worrying about the underlying hardware.
Software (SaaS): This is the "finished house." You just log in and use it. Examples include Gmail, Dropbox, or Slack.
Why Everyone Is Moving Up
Cost-Effective: You trade heavy upfront hardware costs for a "pay-as-you-go" subscription.
Scalable: If your business grows overnight, you can add more power with a single click.
Reliability: Because your data is backed up across multiple global locations, a single hardware crash won't lose your files.
The cloud isn't just a tech trend; it’s the invisible backbone of the modern digital world, making high-powered tech accessible to everyone from solo students to global corporations.
Copilot:
Introduction
Cloud computing is the delivery of computing services—like storage, servers, databases, networking, and software—over the internet. Instead of owning physical hardware, you can access these resources on demand, paying only for what you use. This makes technology more flexible, scalable, and cost-effective.
Key Features
On-Demand Access: Resources are available whenever you need them.
Scalability: Easily increase or decrease capacity based on demand.
Cost Efficiency: No need to invest in expensive hardware; you pay for usage.
Accessibility: Services can be accessed from anywhere with an internet connection.
Types of Cloud Services
1.Infrastructure as a Service (IaaS) – Provides virtual machines, storage, and networking.
2.Platform as a Service (PaaS) – Offers tools for developers to build and deploy applications.
3.Software as a Service (SaaS) – Delivers ready-to-use applications like Gmail or Microsoft 365.
Deployment Models
Public Cloud: Shared services offered by providers like AWS or Azure.
Private Cloud: Dedicated resources for one organization.
Hybrid Cloud: A mix of public and private clouds for flexibility.
Conclusion
Cloud computing is transforming the way individuals and businesses use technology. By offering scalable, affordable, and accessible solutions, it empowers innovation and efficiency in today’s digital world.
FEW SHOT PROMPTING:
PROMPT:
Example 1:
Basics of Drone technology:
Drone technology (UAVs) centers on remote-controlled or autonomous flight, utilizing propellers powered by electric motors, a flight controller for stabilization, and Lithium-polymer (Li-Po) batteries. Key components include a frame, motors, ESCs (Electronic Speed Controllers), GPS for navigation, and sensors like gyroscopes to manage lift, thrust, and stability.
Example 2:
Topic: Basics of human resource and development:
Human Resource Management (HRM) and Development (HRD) focus on managing, training, and optimizing the workforce to achieve organizational goals. Key basics include recruiting, performance management, training/development, and compensation. HRD specifically enhances employee skills through learning, mentoring, and career planning to boost performance. 
Now generate:
Topic: Basics of Drone  Technology with 200 words:
CHATGPT:
Basics of Drone Technology
Drone technology refers to the use of unmanned aerial vehicles (UAVs) that can fly without a human pilot on board. These flying machines are controlled remotely by a person or can operate automatically using programmed software and sensors. Drones were first mainly used for military purposes, but today they are widely used in many civilian applications such as photography, agriculture, surveying, security, and delivery services.
A drone is made up of several important components. The frame provides the structure that holds all the parts together. Propellers and motors help the drone generate lift and move in different directions. A battery supplies the power needed for the drone to operate. The flight controller acts as the brain of the drone, controlling its stability and movement. Many drones also include GPS systems, cameras, and sensors that help in navigation, capturing images, and collecting data.
Drones work by spinning their propellers at different speeds. By adjusting the speed of each motor, the drone can move forward, backward, sideways, or hover in one place. Users typically control drones using a remote controller or a mobile application.
In conclusion, drone technology is an important modern innovation that is transforming industries by making tasks faster, safer, and more efficient. 🚁
GEMINI:
Taking Flight: The Basics of Drone Technology
At its simplest, a drone—formally known as an Unmanned Aerial Vehicle (UAV)—is a flying computer. While they may look like high-tech toys, they are sophisticated machines that blend aerodynamics with advanced robotics.
How They Stay Airborne
Most consumer drones are multirotors, typically quadcopters. They don’t have wings like airplanes; instead, they use four propellers. By varying the speed of each motor, the drone can generate lift, tilt to move forward, or rotate in place. It’s a delicate balancing act performed hundreds of times per second.
The "Brain" and "Senses"
A drone's stability relies on its internal components:

Flight Controller: The "brain" that processes input from the pilot and onboard sensors to keep the craft steady.

IMU (Inertial Measurement Unit): Uses gyroscopes and accelerometers to detect the drone's orientation and prevent it from flipping over.

GPS: Allows the drone to hover in a fixed spot, even in wind, and enables "Return to Home" safety features.

Real-World Impact
Drones aren't just for cool aerial photography anymore. They are currently being used for:
Agriculture: Mapping fields and spraying crops with precision.

Search and Rescue: Using thermal cameras to find missing people in dark or dense terrain.

Infrastructure: Inspecting bridges and power lines safely from the ground.
Whether they are delivering packages or protecting wildlife, drones are redefining what’s possible in the sky.
COPILOT:
Introduction
Drone technology refers to the use of unmanned aerial vehicles (UAVs) that can be remotely controlled or fly autonomously using software and sensors. Originally developed for military purposes, drones are now widely used in industries like agriculture, photography, logistics, and disaster management.
Key Components
Frame: The body structure that holds all parts together.
Propellers & Motors: Provide lift and movement.
Battery: Powers the drone, usually rechargeable lithium-ion.
Controller: A remote device or smartphone app used to guide the drone.
Sensors & GPS: Enable navigation, stability, and autonomous flight.
Camera (optional): Used for aerial photography, videography, or surveillance.
Types of Drones
1.Multi-Rotor Drones – Common for photography and hobby use.
2.Fixed-Wing Drones – Longer flight times, used in mapping and surveying.
3.Hybrid Drones – Combine features of both for versatility.
Applications
Agriculture: Crop monitoring and spraying.
Delivery: Transporting small packages.
Emergency Response: Search and rescue operations.
Entertainment: Aerial filming and racing.
Conclusion
Drones are transforming industries by offering speed, efficiency, and accessibility. As technology advances, they are becoming more affordable and beginner-friendly, making them an exciting tool for both professionals and hobbyists.
CHAIN OF THOUGHT PROMPTS:

PROMPT: EXPLAIN THE BASICS OF drone TECHNOLOGY  IN 200 WORDS, GIVE ME A STEP BY STEP EXPLANATION
Drone technology, or Unmanned Aerial Vehicle (UAV) technology, operates by balancing four aerodynamic forces—lift, weight, thrust, and drag—using spinning propellers. It integrates robotics with aeronautics, combining a lightweight frame, high-torque brushless motors, and smart sensors to achieve stable, controlled flight without a pilot on board. 
XrTech Group +2
Step-by-Step Explanation of How Drones Work:
1.Power Distribution: The Lithium-Polymer (Li-Po) battery supplies electrical energy to the motors and onboard electronics.
2.Thrust Generation: Electronic Speed Controllers (ESCs) receive commands from the flight controller and tell the brushless motors how fast to spin the propellers.
3.Lifting and Stability: Propellers spin at high speeds, forcing air downwards to generate vertical lift (thrust) that exceeds the drone's weight. Two propellers turn clockwise and two counter-clockwise to stabilize the craft and prevent it from spinning uncontrollably.
4.Flight Control (The Brain): The flight controller processes data from sensors—gyroscopes, accelerometers, and magnetometers—in real-time, adjusting motor speeds instantly for stability.
5.Maneuvering (Roll, Pitch, Yaw): By changing the speed of specific propellers, the flight controller tilts the drone (pitch/roll) to move forward, backward, or sideways, and spins it (yaw).
6.Navigation and Communication: The remote controller sends radio signals to the receiver, while GPS, obstacle sensors, and cameras provide data for navigation, mapping, and live video transmission
Chatgpt:
Basics of Drone Technology – Step by Step Explanation
Step 1: Understanding What a Drone Is
A drone is an unmanned aerial vehicle (UAV) that can fly in the air without a human pilot inside it. It is controlled remotely by a user or programmed to fly automatically using software.
Step 2: Main Components of a Drone
A drone consists of several important parts. The frame holds all the components together. Motors and propellers help the drone lift off and move. A battery supplies power, while the flight controller acts as the brain that controls balance and movement.
Step 3: Navigation and Sensors
Most drones include GPS, sensors, and gyroscopes. These components help the drone maintain stability, detect direction, and navigate accurately during flight.
Step 4: How a Drone Flies
Drones fly using multiple propellers that spin at different speeds. By adjusting the speed of each propeller, the drone can move forward, backward, sideways, or hover in one place. The flight controller manages these movements.
Step 5: Control and Communication
Users control drones through a remote controller or smartphone application. The controller sends signals to the drone, allowing the user to guide its movement and capture photos or videos.
Step 6: Applications of Drones
Drone technology is used in many areas such as aerial photography, agriculture, surveillance, delivery services, and disaster management.
Overall, drone technology is a powerful innovation that improves efficiency and safety in many industries. 🚁
Gemini:
Understanding Drone Technology: A Step-by-Step Guide
A drone, or Unmanned Aerial Vehicle (UAV), is an aircraft that flies without a pilot on board. It relies on a fusion of hardware and software to stay airborne and follow commands.
How a Drone Flies: Step-by-Step
Pilot Command: You move a stick on the remote control (Transmitter). This signal is beamed wirelessly to the drone's Receiver.
Processing: The "brain," known as the Flight Controller, receives the command. It checks onboard sensors (like the IMU and GPS) to determine the drone's current orientation and position.
Power Regulation: The brain tells the Electronic Speed Controllers (ESCs) how much power to send to each individual motor.
Propulsion: The Motors spin the Propellers at varying speeds. If the back motors spin faster than the front, the drone tilts forward (Pitch).
Stabilization: Throughout the flight, the drone makes hundreds of tiny adjustments per second to fight wind and stay level, ensuring a smooth hover.
Core Components
Li-Po Battery: Provides the high-density power needed for flight.
IMU Sensor: A combination of gyroscopes and accelerometers that keeps the drone from flipping over.
Gimbal: A motorized mount that keeps the camera steady, even if the drone is tilting.
Copilot:
1. Definition
A drone, also called an Unmanned Aerial Vehicle (UAV), is a flying device controlled remotely or programmed to fly autonomously using sensors and software.
2. Core Components
Frame: The skeleton that holds all parts together.
Propellers & Motors: Generate lift and movement.
Battery: Provides power, usually rechargeable.
Controller: Remote or smartphone app to guide the drone.
Sensors & GPS: Help with navigation, stability, and autonomous flight.
Camera (optional): Captures aerial photos or videos.
3. Types of Drones
Multi-Rotor: Easy to control, used for photography and hobby flying.
Fixed-Wing: Longer flight times, ideal for mapping and surveying.
Hybrid: Combines both for versatility.
4. How Drones Work
1.Power On – Battery supplies energy to motors.
2.Lift-Off – Propellers spin, creating upward thrust.
3.Navigation – GPS and sensors stabilize flight.
4.Control – Pilot uses remote or app to move the drone.
5.Data Capture – Camera or sensors collect information.
6.Landing – Controlled descent until motors stop.
5. Applications
Agriculture (crop monitoring)
Delivery (small packages)
Emergency response (search and rescue)
Entertainment (filming, racing)
Conclusion
Drone technology blends mechanics, electronics, and software to create powerful flying tools. With growing applications, drones are becoming essential in industries and accessible for beginners.
ROLE BASED PROMPTING:
PROMPT:YOU ARE A drone tehcnology EXPERT, GIVE ME AN ARTICLE ABOUT BASICS OF Drone TECHNOLOGY IN 200 WORDS

As a drone technology expert, I recognize that blockchain is revolutionizing unmanned systems by providing a secure, decentralized, and immutable ledger for data management. Unlike traditional centralized databases, blockchain stores information across a network of nodes, making it nearly impossible to hack or alter drone flight logs, sensor data, or mission plans. 

In drone applications, this technology—often called Distributed Ledger Technology—ensures that once data is recorded, it is permanent and transparent. This is crucial for maintaining integrity in autonomous swarm operations or sensitive data logging, as explained on Coursera. Furthermore, blockchain enhances security by replacing centralized trust with cryptographic verification, ensuring that data exchanged within the "Internet of Drones" (IoD) is authentic and tamper-proof. Key advantages for UAVs include decentralized, secure, and unalterable tracking. 

Key Takeaways for Drone Pros:
Immutability: Data cannot be modified or deleted.
Decentralization: No single point of failure.
Security: Cryptographic, peer-to-peer verification
ChatGpt:
Basics of Drone Technology
Drone technology refers to the use of Unmanned Aerial Vehicles (UAVs) that can fly without a human pilot on board. These aircraft are controlled remotely by a user or operate autonomously using programmed instructions and sensors. Drones have rapidly developed in recent years and are now used in many industries such as photography, agriculture, surveillance, delivery services, and disaster management.
A drone is made up of several key components that allow it to function properly. The frame is the structural body that holds all parts together. Motors and propellers generate the thrust needed for the drone to lift off and move in different directions. The battery provides electrical power to the drone. The flight controller, often called the brain of the drone, processes data from sensors and controls the stability and movement of the drone.
Modern drones also include advanced technologies such as GPS modules, gyroscopes, accelerometers, and cameras. These components help the drone maintain balance, navigate accurately, and capture aerial images or videos.
Drones fly by adjusting the speed of their propellers, allowing them to move forward, backward, sideways, or hover in the air. Users typically control them using a remote controller or smartphone application.
Overall, drone technology is an innovative advancement that improves efficiency, safety, and productivity across many fields. 🚁
Gemini:
Eye in the Sky: The Foundations of Drone Tech
Think of a drone, or Unmanned Aerial Vehicle (UAV), as a flying robot that swaps a cockpit for a circuit board. Whether it's a palm-sized toy or a professional cinema rig, the core physics remain the same.
The "Holy Trinity" of Components
To stay airborne, every drone relies on three critical systems:

The Brain (Flight Controller): This is the nerve center. it processes data from sensors like the IMU (Inertial Measurement Unit) to make hundreds of micro-adjustments per second, ensuring the drone doesn't become an expensive lawn dart.

The Muscle (Motors & ESCs): Electronic Speed Controllers (ESCs) act as the middleman, telling the brushless motors exactly how fast to spin By varying motor speeds, the drone can tilt (pitch/roll) or spin (yaw).

The Senses (GPS & Compass): These allow the drone to "know" where it is in 3D space, enabling features like rock-steady hovering and "Return to Home" if the signal drops.

Why It Matters
Modern drones aren't just for hobbyists; they are revolutionizing industries. From thermal imaging for search and rescue to precision agriculture and infrastructure inspection, they provide a "bird’s eye view" without the cost of a helicopter.
The tech is moving fast—much faster than the regulations can keep up with!
Copilot:
Basics of Drone Technology
Drone technology, also known as Unmanned Aerial Vehicle (UAV) technology, is the science and engineering behind flying machines that operate without a human pilot onboard. These devices can be controlled remotely or programmed to fly autonomously using sensors, GPS, and onboard computers.
Core Components
Frame: The structural body that holds all parts.
Propellers & Motors: Generate lift and movement.
Battery: Provides power, usually rechargeable lithium-ion.
Controller: Remote device or smartphone app for navigation.
Sensors & GPS: Ensure stability, positioning, and autonomous flight.
Camera (optional): Captures aerial images or video.
Types of Drones
1.Multi-Rotor Drones – Easy to fly, popular for photography.
2.Fixed-Wing Drones – Longer flight times, used in mapping and surveying.
3.Hybrid Drones – Combine both designs for versatility.
Applications
Agriculture: Crop monitoring and spraying.
Logistics: Package delivery.
Emergency Response: Search and rescue missions.
Entertainment: Aerial filming and racing.
Conclusion
Drone technology blends mechanics, electronics, and software to create powerful flying tools. With growing applications across industries, drones are becoming more affordable and beginner-friendly, making them an exciting innovation for professionals and hobbyists alike.

RESULT:

COMPARISON:

Prompting Technique   	Best Platform  	Accuracy	 Coherence	 Simplicity	 Speed	    User      Experience 
Zero-Shot Prompting	    ChatGPT        	High	       High	       High	     Very Fast	Good	     Clear explanation with balanced detail
Few-Shot Prompting	    ChatGPT       	Very High  	Very High  	Very High	 Moderate	  Excellent	  Step-by-step explanation makes concepts clearer
Role-Based Prompting	  Gemini	        High	       High	      Medium	    Fast	     Good	      More professional and analytical explanation
Chain-of-Thought	      ChatGPT	       Very High	   Very High	Very High	 Moderate	  Excellent	  Step-by-step explanation makes concepts clearer

