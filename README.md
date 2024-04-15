# Hand_Sign_Gesture


The Hand Sign Gesture Communication project aims to bridge the communication gap between deaf individuals and non-deaf individuals who may not be familiar with sign language. This project utilizes computer vision and machine learning techniques to recognize hand signs and translate them into text or spoken language, facilitating communication between these two groups.

**Features:**
1. Hand Sign Recognition: The system can recognize a wide range of hand signs commonly used in sign language.
2. Translation: Detected hand signs are translated into text or spoken language for non-deaf individuals to understand.
3. Real-time Communication: The system operates in real-time, allowing for fluid communication between users.
4. User-Friendly Interface: The interface is designed to be intuitive and accessible for both deaf and non-deaf users.

**Usage:**
1. Start the application and position the camera to capture the user's hand gestures.
2. Perform hand signs in front of the camera.
3. The system will recognize the hand signs and display the corresponding handsign to text message.
4. Communicate effectively with non-deaf individuals using the translated output.

**Requirements:**
- Webcam or camera-enabled device
- Python environment with necessary libraries.
- Create an virtual environment to run this code.

**Dependencies:**
```
pip install opency-python
```
```
pip install cvzone
```
```
pip install numpy
```

**Installation:**
1. Clone this github repository, using the command in cmd.
```
git clone (the link of this repo)
```
2.Install the required dependencies using the above commands.
3. Create a folder to save the data and whithin that create folders for specific handsigns in which the data is to be stored.
4. Run the datacollection.py file to get the data by changing the path of the folder. 
5. After collecting the data go to https://teachablemachine.withgoogle.com/train/image to train the data collected.
6. Download the keras file in that and add the kerad.h5 file path in the test.py file.
7. Run the test.py folder to start the Hand Sign Gesture Communication system.

Happy Reading :)
