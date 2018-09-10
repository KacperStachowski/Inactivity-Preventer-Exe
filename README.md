#######################################################
INACTIVITY PREVENTER

Created by: Kacper Stachowski (k.stachowski92@gmail.com)
Art by: Kaja Kosmala (nemezis1314@gmail.com)

Exe downloaded from: https://github.com/KacperStachowski/Inactivity-Preventer-Exe
Code can be found at: https://github.com/KacperStachowski/Inactivity-Preventer


Inactivity Preventer is a simple desktop application that prevents PC and Skype from going into inactive state when you can't change system settings manually.

It moves a mouse pointer for a number of times randomly picked from a range selected by the user in interval selected from range of 5 to 300 seconds. Each action can also be configured to write some text per each mouse move.

#######################################################
PROPERTIES:

* Actions per loop: [X] - [Y] 
Defines a range of numbers from which a random number of actions to be performed will be picked. New, random number of actions is picked from the same range after each loop is finished.

[X] - Defines a starting number of range. Minimum value is 5, maximum is 98. The value will be set to minimum value automatically if an user inputs a non-numeric value or value lower than 5. The number will be set to maximum value if an user inputs value higher than 98.

[Y] - Defines an ending number of range. Minimum value is [X] + 1, maximum is 99. The number will be set to minimum value automatically if an user inputs a non-numeric value or value lower than [X].


* Interval: [Z] seconds
[Z] - Defines a time that has to pass between each actions set to be performed. Mimimum value is 5, maximum value is 300. The value will be set to minimum value automatically if an user inputs a non-numeric value or value lower than 5. The number will be set to maximum value if an user inputs value higher than 300.

* Use keyboar while performing action
Defines if each action in an actions set will also consist of inputting a text from [Text written per action:] textbox. If this checkbox is selected, a text will be typed automatically after each mouse move while performing action, as many times as actions number selected from [Actions per loop:] range.

!TIP
While Inactivity Preventer is working, it will type text to a currently active window, meaning that if an user starts the application and clicks on something else like notepad or a website, the application will type text into the currently active window. Remember to focus Inactivity Preventer window when you are not working on your PC. 

!TIP
In some cases using keyboard while performing actions will be required to keep your PC and Skype from going inactive.
