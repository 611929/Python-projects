# Alarm-Clock

Creating an Alarm Clock in Python (GUI)
In this python project, we will create a GUI-based alarm clock using the Tkinter module. 

About Python Alarm Clock Project
The objective of this python project is to create a GUI based Alarm Clock. You will only need a basic understanding of winsound, Tkinter, and datetime libraries to create this project. 

Project Prerequisites:
To develop this python project, you need basic knowledge of the Python language and Tkinter library. We are going to need the following libraries:

Tkinter: For the creation of the GUI
Datetime: To get the current date and time from the system
Time: To suspend the execution of the program for some time
Winsound: To play a sound on the computer
All the libraries come pre-installed with Python.

Python Alarm Clock – Project File Structure
Here are all the steps that you will have to do to create this project.

1)Importing all the necessary libraries.

2)Defining a function for the alarm clock when the time comes.

3)Creating the master GUI window and placing all the components in it.

# 3.Defining a function for the alarm clock:
Explanation:

datetime.datetime.now(): This function returns the date and time according to the local time. The .strftime() method is generally used to get specific data from this function. So the “%H:%M:%S” argument gives us the current hour, minute, and second. At the specified time our python alarm clock will ring the alarm.

winsound.Playsound(): This function takes 2 arguments: ‘filename’ and flag. The filename must be a .wav file since that is the only format this function is compatible with. The flag argument is used to refer to the output file. 

Output:


![image](https://user-images.githubusercontent.com/91775706/135707187-4224f584-2632-489c-9b98-4b2909c03be6.png)


Summary:

Now, we have successfully created python alarm clock using Tkinter, winsound, and datetime modules.

WARNING!!
You will have to keep the computer running if you want the alarm to work. Also, the .wav file that you want to ring at the time of the alarm, should be in the same directory as your code .py file.
