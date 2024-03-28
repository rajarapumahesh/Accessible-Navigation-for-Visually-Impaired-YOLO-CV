# Accessible-Navigation-for-Visually-Impaired-YOLO-CV
**Overview**
The Accessible Navigation for Visually Impaired project aims to assist visually impaired individuals in navigating indoor environments using computer vision technology. The system is designed to detect obstacles, identify landmarks, and provide audio feedback to help users navigate safely and independently.

**Project Details**
**Object Detection**
The core functionality of the system is based on real-time object detection using the YOLO (You Only Look Once) algorithm. YOLO is a state-of-the-art deep learning model that enables fast and accurate object detection in images and video streams. By leveraging YOLO, the system can identify various objects in the environment, such as doors, chairs, tables, and people.

**Distance Estimation**
The system estimates the distance between the user and detected objects to determine their proximity. This distance estimation is crucial for providing accurate navigation guidance to the visually impaired user. Using mathematical calculations based on the object's size and position in the image, the system can approximate the distance between the user and each detected object.

**Audio Feedback**
Upon detecting objects within a certain range, the system provides audio feedback to the user. The feedback includes information about the type of object detected, its distance from the user, and its relative direction (e.g., left, right, front, behind). This audio feedback is essential for guiding the user through the environment and alerting them to potential obstacles in their path.

**Parallel Video Playback**
In addition to audio feedback, the system displays a parallel video feed with bounding boxes around detected objects. This visual representation allows sighted individuals, such as caregivers or volunteers, to monitor the user's surroundings and assist as needed. The bounding boxes serve as a visual aid, highlighting the location of objects detected by the system.

**Usage**
To use the Accessible Navigation for Visually Impaired system:

Ensure that you have the necessary dependencies installed, including Python, OpenCV, and pyttsx3.
Download the YOLO pre-trained weights, configuration file, and class labels from the official YOLO website or repository.
Update the file paths in the project code to point to the downloaded files.
Run the main script, providing the path to the video feed as input.
Observe the system's audio feedback and parallel video playback as it detects and identifies objects in the environment.
