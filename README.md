# Generalized Hand Gesture Recognition System

## Overview

We have developed a breakthrough hand gesture recognition system that adapts across diverse applications, leveraging advanced machine learning techniques to interpret gestures accurately. This system empowers users with natural and efficient interaction, making it ideal for video conferencing, sign language communication, and intuitive smart home control. By using edge-based inference, our system ensures real-time responsiveness, reflecting the fluidity of human communication. This innovation aims to revolutionize human-computer interaction, promote inclusivity, and unlock a myriad of possibilities.
<img width="246" alt="gui" src="https://github.com/dheerajkallakuri/Generalized-Hand-Gesture-Recognition/assets/23552796/8636a96e-41b2-487d-9da1-b2b3b9ebc1fa">

## Applications

### 1. Video Conference and Communication Systems
Our system enhances video conferencing experiences by integrating gesture-based controls, allowing users to navigate digital spaces naturally and expressively. This non-verbal interaction fosters a deeper connection in remote collaboration settings, enhancing communication and productivity.
<img width="200" alt="HaGRID" src="https://github.com/dheerajkallakuri/Generalized-Hand-Gesture-Recognition/assets/23552796/2aff3d31-70f3-4fed-b493-88bc0bb4105c">

### 2. American Sign Language (ASL) Communication
The sign language detector translates gestures into spoken words, helping individuals who are deaf or mute to communicate effectively. This tool promotes inclusivity in education, employment, and social interactions, empowering individuals and celebrating sign language cultures.
<img width="237" alt="sign_data" src="https://github.com/dheerajkallakuri/Generalized-Hand-Gesture-Recognition/assets/23552796/67f7bff8-b9b7-4d31-b3b3-21e2c410da64">

### 3. Media Control
Our technology transforms media interaction, enabling intuitive control over music, movies, and more. This enhances personal entertainment, presentations, and smart home experiences, making technology more accessible and enjoyable.

## Running the Applications

To use all applications in a single GUI, run:
```
python app.py
```

### Video Conference and Communication Systems
To run this application:
```
python gesture_detection.py
```
<img width="241" alt="gesture" src="https://github.com/dheerajkallakuri/Generalized-Hand-Gesture-Recognition/assets/23552796/5fc4b2b9-2003-439b-b715-b2ed5ed407fb">


### American Sign Language (ASL) Communication
To run this application:
```
python sign_language.py
```
<img width="250" alt="sign" src="https://github.com/dheerajkallakuri/Generalized-Hand-Gesture-Recognition/assets/23552796/bbe78033-7c57-4a8e-8c60-1ae6ab8b344c">


To train the ASL alphabet from scratch:
1. Collect images for 26 alphabets:
    ```
    python collect_imgs.py
    ```
2. Create a dataset:
    ```
    python create_dataset.py
    ```
3. Train the classifier:
    ```
    python train_classifer.py
    ```
4. Use the trained model for detection:
    ```
    model.p
    ```

### Media Control
To run this application:
```
python media_control.py
```
<img width="244" alt="media" src="https://github.com/dheerajkallakuri/Generalized-Hand-Gesture-Recognition/assets/23552796/e87d59e9-2bcd-436c-b5e9-e189f4e89af4">

## Project Resources

- **Project Presentation:** [presentation.pdf](Presentation.pdf)
- **Project Repository:**
  [![Project Video Demonstration](https://img.youtube.com/vi/tW3jClIxz8g/0.jpg)](https://www.youtube.com/watch?v=tW3jClIxz8g)

Thank you for using our Generalized Hand Gesture Recognition System! We look forward to your feedback and contributions.
