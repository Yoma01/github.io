#### Robotic Assistant for Finding Misplaced Objects
Mild Cognitive Impairment (MCI) manifests as an early-stage decline in cognitive abilities such as memory and perception, affecting 3-19% of individuals over 65 years old. One prominent symptom is misplacing objects due to memory lapses. To mitigate this challenge, my team members and I devised a solution: an object tracking robot. Our robot autonomously navigates homes, capturing images at predetermined locations. These images undergo object classification, and their details are stored in a JSON database including timestamps and locations. When prompted, the system retrieves relevant images of misplaced items, displaying them for user verification. Guiding users to the object's location, the robot enhances independence and alleviates frustration associated with MCI-related memory difficulties.

Skills/FrameWorks/Tools Used: Python programming, Robotic Operating System (ROS), Hello Robot Stretch RE2, Object Detection Models

[Robotic Assistant Repo](https://github.com/JuanRobledo12/blue_stretch)

<p align="center">
  <a href="https://www.youtube.com/watch?v=QUB79UTbwvE" target="_blank">
   <img src="static/assets/img/THUMBNAIL.png" alt="Robotic Assistant" width="500" height="262" border="0" />
  </a>
</p>

#### Other ROS Projects
Other ROS projects and demos may be seen in this repository:
[ROS Projects Repo](https://github.com/TofunmiSodimu/ROS-projects)

#### Kelp Segmentation 
This project introduces the problem of kelp forest conservation, highlighting the ecological and economic significance of these marine habitats while addressing threats like climate change and overfishing. We propose leveraging technology, specifically satellite imagery and machine learning, to monitor and protect kelp forests. Our main focus was on developing a convolutional neural network (CNN) model for kelp segmentation, using various satellite image channels like SWIR, NIR, and NDVI. We compare our approach with existing literature, showcasing advancements and challenges in kelp detection. We detail the UNET architecture used, along with experiments on model parameters and data preprocessing techniques. Our results indicate progress but also reveal challenges like computational resource limitations and dataset errors. Future directions include refining the model, improving computational efficiency, and deploying it in real-world scenarios for practical conservation efforts.

<p align="center">
  <img src="static/assets/img/kelp.png" alt="Results of Kelp Segmentation" width="500"/>
</p>

Skills/FrameWorks/Tools Used: Python programming, Convolutional Neural Networks, Deep Learning, Pytorch, Tensorflow, Scikit Learn, MatplotLib, Numpy, Pandas

[Kelp Segmentation Repo](https://github.com/nadira30/kelp_segmentation)

#### Other Computer Vision Projects
Other computer vision projects and demos may be seen in this repository:
[Computer Vision Projects Repo](https://github.com/TofunmiSodimu/Computer_Vision)

#### Anomaly Detection of Object Locations
Innovating beyond conventional object tracking, this project expands capabilities to preemptively identify misplaced objects and initiate appropriate follow-up actions. A key development is a Convolutional Neural Network (CNN) model trained on scene graphs extracted from a comprehensive dataset of household routines spanning 50 days (HOMER-PLUS Dataset). This model discerns anomalous object locations, enhancing the system's proactive functionality. For further insights into this project, please refer to the GitHub repository.

Skills/FrameWorks/Tools Used: Python programming, Convolutional Neural Networks, Deep Learning, Pytorch, Tensorflow, Scikit Learn, MatplotLib, Numpy, Pandas

[Anomaly Detection Repo](https://github.com/TofunmiSodimu/Novelty-Detection)

#### Path Planning to Control Robotic Arm for Suturing
In this work, my partner and I conduct path planning and end effector modifications for a 5 DOF xARM robot, computing forward kinematics and implementing resolved rates for path planning, with findings transferred to the physical robot using Arduino. Additionally, we provide access to MATLAB code for simulations and final demo videos. Suturing, a critical medical procedure, often poses challenges such as tediousness and dependency on practitioner dexterity, motivating the need for automation, particularly in minimally-invasive procedures. While existing Robotic Surgical Assistants (RSAs) address this need, we aim to demonstrate automated suturing with an already available robotic arm, from assembly to modifications, forward kinematics determination, path planning, and communication establishment. The 5 DOF + gripper robotic arm, purchased from Lewansoul, is described along with modifications to enhance needle grip. Forward kinematics are derived and validated through MATLAB simulations, and path planning involves resolved rates algorithm implementation for both straight needle insertion and scenarios with constrained joint angles. Communication between the robotic arm, MATLAB, and Arduino is established for control and feedback. A tissue replica is developed to demonstrate suturing, with adjustments made to accommodate the robotic arm's accuracy limitations. For further insights, access to our project video, presentation slides, and code repository is provided, showcasing the feasibility of automated suturing using an existing robotic arm and paving the way for enhanced surgical automation and precision.

[Path Planning Repo](https://amritpal-001.github.io/projects/2022-medical-robotics-kinematics)

Skills/FrameWorks/Tools Used: MATLAB, Arduino, Mechanics, Forward/Inverse Kinematics, Computer Aided Design (CAD)

#### Bladder Fluid Flowscope
In this project my team members and I created a device to measure the volume of fluid perfused into the bladder during cystoscopy procedures, because urrent methods lack accuracy and efficiency, prompting the need for a reliable solution. This device, powered by a battery and featuring a real-time display, enables precise measurements up to 1 liter of fluid with a tolerance of ±4mL. Benefits include improved diagnostic accuracy, standardized data for patient monitoring, and enhanced efficiency in urological procedures. The device's specifications ensure compatibility with surgical environments, with options for disposable or sterilizable versions within a cost-effective range. This innovative project not only addresses a critical need in healthcare but also fosters collaboration between academia and medical practice, promising advancements in patient care and opportunities for future research and development.
Over the course of the project, I developed the electrical schematic and implemented the circuitry for the device enabling us to measure volumes of 0 – 1000mL with an accuracy of +/- 4mL per our client’s specifications. I developed an Arduino program to determine volume based on the voltage signal from the load cell and the density of the fluid, and to display the calculated volume, to the nearest mL, in real time. Additionally, I provided effective leadership for a group of 5 students leading to the successful completion of the project, and maintained regular and effective communication between client, team mentor, and team members.

Skills/FrameWorks/Tools Used: Arduino, Mechanics, Computer Aided Design (CAD)
