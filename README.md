# Python-Jupyter-Mini-Project

George Stathopoulos

Professor Marano

CS 102

12/17/2021

 In this project I designed  an  automated  law  enforcement  system  that  will  issue  tickets to speeding drivers on a given stretch of a “smart highway”.  This road contains sensors that determine the speed of all vehicles it carries and license plate readers that can uniquely identify all vehicles. Using google colab, which allowed me to combine executable code and rich text in a single document, along with images and more [1], I developed  a  program in Python that  determines  the  time  and  number  of speeding  ticket(s)  to  be  issued  to  a  driver. I did so using two files.  The  first  file (driving_data.csv) contains a Comma Separated Value (CSV) series of timestamps and vehicle speeds,  one  sample  per  line (time  in  minutes,  speed  in  MPH),  taken from  an  automobile’s  onboard computer.  The second file (speedlimit.csv) contains a matching series of timestamps and speed  limits. The  timestamp  in  this  file  indicates  the  time  in  minutes  at  which  the  vehicle encountered the given speed limit.  In Python, I was able to load each file and construct appropriate logic to determine when violations occurred. The main aspect of this logic being a function “speeding” that returns “True” if the driver's speed is greater than the speed limit at that specific time and “False” if not. The program then outputs a .csv file that has columns corresponding to the time, the driver's speed at that time, and whether or not the driver was speeding. This was the main function of my code, but there were many other little aspects of the code that were required to make it run. Explanations of these can be found integrated in the code itself as text. The main things to note from the blocks of texts are my use of matplotlib and pandas. Matplotlib is a cross-platform, data visualization and graphical plotting library for Python and its numerical extension NumPy [2]. It is what I used to later create a graph. Pandas is a python library for data manipulation and analysis [3]. Finally, the code prints a graph of “Speed in MPH” with respect to “Time (Minutes)”. In the future, a system could eventually be created that reads these outputs and distributes tickets when a violation is recorded.

# References:

1. Google Colab, Google, https://colab.research.google.com/?utm_source=scs-index. 
2. “The Open Source Languages Company.” ActiveState, 15 Dec. 2021, http://www.activestate.com/. 
3. “Simpllilearn.com - Simpllilearn Resources and Information.” Simpllilearn.com - Simpllilearn Resources and Information., http://www.simpllilearn.com/. 

