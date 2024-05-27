# SmartRobot
This project addresses the challenges of maintaining large-scale farms that use tractors and heavy machinery, which often damage irrigation water pipes. The solution is an autonomous robot that ensures efficient irrigation without water pipes, preventing infrastructure damage and ensuring consistent water distribution.


# Features
- Android Studio App: Customized application to display real-time temperature and historical graphs for humidity, temperature, and soil moisture variables.
- Firebase Integration: Stores data sent by ESP32 devices. The data is overwritten with each new value sent.
- ESP32 Communication: Uses two ESP32 devices that communicate to send and receive signals from real-time conditions.
# Technologies Used
- ESP32 IoT: For real-time data collection and communication.
- Firebase: For storing and retrieving data.
- Android Studio: For developing the mobile application.
# How It Works
- Data Collection: The project begins with a stationary ESP32 that sends data to Firebase when there is low soil moisture or low humidity.
- Data Reception: An ESP32 located on the robot receives data from Firebase and starts to move towards the location.
- Navigation and Detection: The robot is guided by a line-following parameter and can detect the pot using a color sensor located beneath the robot.
# Documentation & mobile application images

For a comprehensive demonstration of the Smart-Aquarium in action, please watch the [Video Demonstration]().

![image](https://github.com/RaphaelNazareth/FarmRobot/assets/86475236/593181e4-422b-4763-b940-9c1653388ca6)

*image: first page of the application*

![image](https://github.com/RaphaelNazareth/FarmRobot/assets/86475236/b0ddd23a-3d56-4f3d-9a75-00cd718c8e65)


*image: interactable login page with local database*

![image](https://github.com/RaphaelNazareth/FarmRobot/assets/86475236/a457179a-719e-4998-91f4-44ee3eabb2b5)


*image: homepage for monitoring sensors & interactable circular progress bar*

![image](https://github.com/RaphaelNazareth/FarmRobot/assets/86475236/f7212ed3-da26-46a4-b1a8-5bda4eb37e8c)


*image: Temperature page with historical graph and Circular Progress Bar *

![image](https://github.com/RaphaelNazareth/FarmRobot/assets/86475236/9cb01fd8-e5e6-4aea-9c5d-5a4997312104)


*image: Soil moisture page with historical graph and Circular Progress Bar *

![image](https://github.com/RaphaelNazareth/FarmRobot/assets/86475236/faa350bc-0eb9-4aa2-85b9-33c58eaf03ce)


*image: Humidity page with historical graph and Circular Progress Bar *

[Return to top](https://github.com/RaphaelNazareth/FarmRobot)
