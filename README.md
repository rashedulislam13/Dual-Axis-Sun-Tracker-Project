This project aims to design and implement a smart home security system capable of human detection, utilizing the efficiency of PIR (Passive Infrared) sensors and advanced image processing with a Raspberry Pi 3. The system is developed to enhance home security by detecting potential intruders or unauthorized individuals and sending real-time alerts to homeowners.

The PIR sensor, installed on an Arduino, functions as the main motion detection device. It identifies changes in infrared radiation, typically emitted by humans. When motion is detected, the PIR sensor sends a signal to trigger the next phase of the system.

A webcam is mounted on the Raspberry Pi 3, which handles image capturing and processing. Upon receiving the signal from the PIR sensor, the webcam captures an image. The Raspberry Pi 3, equipped with sufficient computational power, processes the image to determine whether the detected object is human using object recognition algorithms.

This setup ensures real-time image analysis and swift decision-making. By integrating the Raspberry Pi and the Arduino, the system operates seamlessly to detect motion and verify human presence, minimizing false alarms.

If a human is detected, an alert is sent to the homeowner via a mobile app or SMS, enabling them to take immediate action. This instant notification system improves the overall security by preventing unauthorized entry or intrusions.

The smart home security system offers an affordable and efficient solution by using readily available components like the PIR sensor, Arduino, and Raspberry Pi 3. The design is flexible and can be upgraded with more sensors or advanced algorithms to improve detection accuracy in the future.
