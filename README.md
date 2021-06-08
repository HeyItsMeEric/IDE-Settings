# IDE Settings

# Language keyword colors:

Java 240, 0, 180 (CC00B4)

Python (FF9F2F)

C/C++ 14, 155, 226 (0E9BE2)

C# 77, 174, 132 (4DAE84)

Javascript 238, 58, 58 (EE3A3A)


Visual Studio Code Plugins:
PlatformIO (same as the Jetbrains one)




Jetbrains Plugins to install:

Code glance - All (like map mode for Visual Studio)
PlatformIO - For embedded systems, i.e. Arduino and such (CLion)
Java Decompiler (IntelliJ)




For Whatever reason, JetBrains Rider for C# does not follow the normal Velocity Template Langauge their other products support...

To get the current date and time for a file template, use the following format:   MMMM dd, yyyy, hh:mm:ss tt  
M = month, d = day, y = year, h = hour, m = minute, s = second, tt = AM or PM.
You can also specify "MM" for the month number, "yy" for the last two digits of the year, "ffff" OR "FFFF" for time in milliseconds (i think), "gggg" for A.D., and "dddd" for the day of the week

Here is how to set this up:
![img.png](ReadMe%20Photos/Rider%20File%20Template%20Navigation.png)
Go through these steps



![img_2.png](ReadMe%20Photos/Date%20format%20expression.png)
Go back to the macro window and now a box should appear where you should put the format. Note that anything put in quotation marks will NOT be evaluated (like the "at")




![img_3.png](ReadMe%20Photos/Template%20output.png)
Output
