# Alarm-Clock

The goal of the project is to create a simple alarm clock using Python and the Tkinter library. The user can set the time for the alarm and when the alarm time is reached, the program will play a sound to wake up the user. The project also demonstrates the use of multithreading in Python to allow the alarm to run in the background while the user interface remains responsive.

## Instructions to run the game

* Install Python on your computer if you haven't already. You can download Python from the official website: https://www.python.org/downloads/

* Open a text editor and copy the code into it.

* Save the file with a .py extension.

* Download the sound file named "sound.wav" and save it in the same directory as the Python file.

* Open a terminal or command prompt and navigate to the directory where you saved the Python file.

* Type the command python filename.py and press enter to run the code.

* The GUI window for the alarm clock will appear. Select the time for the alarm using the dropdown menus and click on the "Set Alarm" button to set the alarm.

* Once the alarm is set, the program will run in the background until the alarm time is reached. When the alarm time is reached, a message will be printed on the console and a sound will play.


## Functionality of the code

This code is for a simple alarm clock program using Python's Tkinter GUI toolkit. It allows the user to set the desired alarm time by selecting the hour, minute, and second using three drop-down menus. Once the "Set Alarm" button is clicked, the program starts a new thread that runs an infinite loop to check whether the current time matches the set alarm time or not. If the time matches, it plays a sound (sound.wav) to wake up the user.

The program uses the following libraries:

* tkinter: for the GUI interface
* datetime: for getting the current time
* time: for waiting for one second
* winsound: for playing sound
* threading: for creating a new thread

