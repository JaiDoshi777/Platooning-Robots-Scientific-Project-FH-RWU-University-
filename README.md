# Platooning-Robots-Scientific-Project-FH-RWU-University-
Designed and implemented an autonomous robot capable of following a leading vehicle while maintaining a safe distance using cost-effective vision-based technologies.

The project titled "Platooning Autonomous Following Robot" focuses on the development of an autonomous robot capable of following a leading vehicle without human intervention. This initiative is part of a Master's program in Mechatronics at the University of Applied Sciences Ravensburg-Weingarten, guided by Prof. Dr. Stefan Elser. The primary objective of the project is to create a cost-effective solution that utilizes computer vision and ArUco markers for navigation, thereby eliminating the need for expensive sensors like LiDAR. The system is designed to maintain a safe distance from the leading vehicle while adapting to various environmental conditions, showcasing its potential for enhancing the safety and efficiency of autonomous driving technologies.

The project employs a Raspberry Pi 4 as the central processing unit, integrating various hardware components such as DC motors, a camera module, and a power supply system. The robot's locomotion is facilitated by two DC motors controlled through a motor shield, allowing for precise movement and direction adjustments. The camera module plays a crucial role in capturing real-time images of the environment, which are processed using advanced computer vision algorithms. The integration of ArUco markers enables the robot to accurately track the leading vehicle's position, facilitating effective communication and navigation between the two robots. The project emphasizes the importance of hardware integration and software development, ensuring that all components work seamlessly to achieve the desired autonomous following behavior.

A significant aspect of the project is the implementation of sophisticated control algorithms that process sensor data and manage the robot's navigation. The algorithms are designed to calculate the distance to the leading vehicle and make real-time adjustments to the follower robot's speed and direction. The use of a Kalman filter enhances the accuracy of these measurements by filtering out noise and inconsistencies in the visual data. This approach allows the robot to maintain a consistent following distance, even in dynamic environments where the leading vehicle may change speed or direction. Extensive testing has demonstrated the system's robustness, with the robot successfully navigating various scenarios while maintaining a safe distance from the leading vehicle.

Throughout the project, the team encountered several challenges, including hardware limitations, environmental factors, and the need for real-time processing capabilities. The initial use of low-quality motors led to difficulties in maintaining a straight path, which was addressed by applying correction factors based on surface conditions. Additionally, the PiCamera's overheating issues during high-resolution video capture prompted a switch to the OpenCV library for more efficient camera handling. The project also highlighted the impact of lighting conditions on ArUco marker detection, emphasizing the need for consistent indoor lighting to ensure reliable performance. These challenges provided valuable insights into the complexities of developing autonomous systems and underscored the importance of iterative testing and refinement.

In conclusion, the "Platooning Autonomous Following Robot" project represents a significant advancement in the field of autonomous vehicle technology. By successfully demonstrating a cost-effective and scalable solution for autonomous following, the project contributes to the broader domain of autonomous driving applications. The integration of computer vision techniques with practical robotics showcases the potential for enhancing transportation efficiency and safety. Future work may involve the incorporation of additional sensors, refinement of motor control algorithms, and exploration of advanced image processing techniques to further improve the system's capabilities. Overall, this project not only achieves its technical objectives but also lays the groundwork for further research and development in autonomous systems.

![image](https://github.com/user-attachments/assets/0efb2619-3b99-4734-9367-aff14cc3619d)
Platooning of Robots

![iMAGE !](https://github.com/user-attachments/assets/eae1442c-e345-4cbd-bba6-05cc501e34a9)

Test Image with ArUco markers


![image](https://github.com/user-attachments/assets/36d54619-5a44-4606-b309-aafe5cbd5f83) 


