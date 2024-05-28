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

![Screenshot 2024-05-27 191340](https://github.com/RaphaelNazareth/Farm-Robot/assets/86475236/0f248f23-bd08-404b-8b2a-7a2b81adcd81)


*image: first page of the application*

![Screenshot 2024-05-27 191411](https://github.com/RaphaelNazareth/Farm-Robot/assets/86475236/3271c836-c051-4879-b4f6-55a21e531e94)


*image: interactable login page with local database*

![Screenshot 2024-05-27 191455](https://github.com/RaphaelNazareth/Farm-Robot/assets/86475236/cc6c2ee1-ace5-4117-8ebb-147151a7a4cb)

*image: homepage for monitoring sensors & interactable circular progress bar*

![Screenshot 2024-05-27 191741](https://github.com/RaphaelNazareth/Farm-Robot/assets/86475236/6b7653a3-4a45-4514-8867-6cd461817aaf)

*image: Temperature page with historical graph and Circular Progress Bar *

![Screenshot 2024-05-27 191810](https://github.com/RaphaelNazareth/Farm-Robot/assets/86475236/02531bfb-a09d-42fc-90a4-b5573f2049af)

*image: Soil moisture page with historical graph and Circular Progress Bar *

![Screenshot 2024-05-27 191832](https://github.com/RaphaelNazareth/Farm-Robot/assets/86475236/aa436891-7426-4572-b1a0-0a2d1ec70ad5)

*image: Humidity page with historical graph and Circular Progress Bar *

[Return to top](https://github.com/RaphaelNazareth/FarmRobot)
