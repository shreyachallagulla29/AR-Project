# Project-Augmented Reality in Education

Project File:
https://drive.google.com/drive/folders/1EQA8Yar_zomo_y_SDlDi-nTFumYW-Wq4

The above link has all the packages,assets and files

## Augmented Reality Textbook Application
### Overview
This Unity 3D project is an Augmented Reality (AR) application designed to enhance the learning experience by overlaying videos related to textbook pages. The project uses Vuforia Engine to create interactive AR experiences where each textbook page is associated with a specific video. Upon scanning a page in the textbook, the corresponding video content will appear in augmented reality.

### Features
AR Textbook Integration: Each page in the textbook has a unique video that provides additional context or explanation for the content on that page.

Vuforia Engine: Utilizes the Vuforia AR platform to track and recognize pages in the textbook, triggering the display of the associated video in the AR environment.

Interactive Learning: Allows users to interact with textbook content in an immersive and engaging way.

###  Requirements
Unity 3D: This project has been developed in Unity 3D.

Vuforia Engine: Make sure the Vuforia Engine is imported and set up in your Unity project.

AR-enabled Device: An Android or iOS device with AR capabilities for testing the application.

Vuforia SDK: Ensure that the Vuforia SDK is properly installed and configured in your Unity project.

### Getting Started
1. Clone or Download the Repository
Download the Unity project from the provided link or clone it into your preferred directory.

2. Install Unity and Vuforia
Install Unity Hub and the latest version of Unity.
Make sure to add the Vuforia Engine module through the Unity Hub during installation or via the Unity Package Manager.

3. Open the Project
Open the Unity project in Unity Hub.
Ensure that the Vuforia Engine has been properly imported into your project. If not, go to Window -> Package Manager and add Vuforia Engine.

4. Set Up Vuforia
Activate Vuforia: In the Unity Editor, go to Edit -> Project Settings -> Player and enable Vuforia in the XR Settings.
License Key: Make sure your Vuforia license key is added under Vuforia Configuration in the Player Settings.

5. Add the AR Camera
The scene should already include the AR Camera prefab from Vuforia.
Ensure that the camera is set up correctly to detect the textbook pages.

6. Add the Textbook Pages and Videos
Each textbook page is set up as an Image Target in Vuforia.
In Unity, you should have the image targets corresponding to the pages of your textbook.
The video associated with each page is assigned to the target via the Video Player component.
You can place the videos on the UI canvas or in the 3D space, depending on your design preferences.

7. Build Settings
Platform: Make sure the build target is set to either Android or iOS, depending on your testing device.
AR Requirements: Enable AR features in the Unity Build Settings for your target platform.

8. Run the Application
Connect your AR-enabled device to your computer.
Run the application through Unity and test the AR experience by scanning a textbook page.
The corresponding video should play once the page is recognized.

### Troubleshooting
Vuforia Engine Not Recognizing Pages: Ensure the images you are using for Image Targets have sufficient contrast and are clearly visible for the AR camera.
Video Not Playing: Check that the Video Player component is correctly set up with the video file and is linked to the corresponding page's image target.
