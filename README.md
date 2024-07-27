1.	Download Python 3.9 for Windows. When installing, make sure it sets the path. We will check this later in the environmental variables. 
2.	Download Python extension for Visual Studio Code (VSC).
3.	Change the Python interpreter path in VSC to the same location as where Python 3.9 would be installed on your computer (to know if you're in the right placethe Python 3.9 path should have lib folders). 
    Follow the instructions in this link: https://www.youtube.com/watch?v=WwmsvJWHx0Y (Programs>python>python39>python.exe).
5.	Search up (the magnifying glass on your taskbar in Windows 11) "Edit the system environmental variables".
    A window called "System Properties" should pop up. Click on the "Environmental Variables" button.
  	Under System Variables > Path, change the path to the same place where Python 3.9 would be installed on your computer (the same path as step 3). This should match the visual studio code. 
9.	Download the zipped file above and Copy the two files pybluez.023 and Bluetooth.
10. Put it in the Python 39> lib> site packages. To know if you're in the right place, the pip and pip 24.1 (depends on version) folders should be there. 
12.	Test to see if it's instaleld by putting "pip install pybluez" into any cmd. It should say requirement already satisfied. It should show that the pybluez file (that we added from the zip) is there.

Hopefully this works! :) 
