# IoT-Automatic-Fish-Feeder-Website
This project is an automatic fish feeder system that combines an Arduino Uno–based hardware setup with a supporting website for documentation and presentation. The system is designed to automate the fish feeding process, helping aquarium owners provide food efficiently without constant manual intervention.

At the core of the hardware is an Arduino Uno microcontroller that manages all system operations. An HC-SR04 ultrasonic sensor is used to detect the presence of an object within a predefined distance of 5 cm. When an object enters the detection range, the Arduino processes the sensor data and triggers a 9g servo motor to operate the feeding mechanism.

The servo motor automatically opens the food dispenser, allowing fish feed to be released from the storage container into the aquarium. Once the feeding process is completed, the servo returns to its original position, preventing excess food from being dispensed. The entire operation is performed automatically based on sensor input and programmed logic.

The project demonstrates fundamental concepts of embedded systems, including sensor-based input, conditional logic, actuator control, and automated mechanical operation. All components used are affordable, widely available, and suitable for beginners learning Arduino-based automation and Internet of Things (IoT) applications.

In addition to the hardware system, a dedicated website was created to present the project. The website serves as a central repository for explaining the system concept, hardware components, wiring configuration, logic flow, and overall functionality. It improves clarity, accessibility, and professionalism by allowing others to understand the project without direct access to the physical setup.

Overall, this project functions as an educational prototype for an IoT-based automatic fish feeding system. It highlights practical integration between hardware automation and web-based presentation, making it suitable for learning, demonstrations, and basic real-world simulation purposes.
