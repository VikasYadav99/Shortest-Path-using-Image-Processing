# Shortest-Path-using-Image-Processing-using-Dijkstra's-Algorithm

#
**Using Image Processing this code finds a shortest path between two junctions in the given image of line maze.**
 
There are 3 python scripts named path_finding.py, helper_functions.py, helper_class.py 
path_finding.py is the main script. 
cv2 and numpy are the modules used. 

#
**Flow of code:** 
 
Image is read, resized, transformed and filtered to find junctions. 
These junction co-ordinates are then used to make a graph. 
This graph is then used to find shortest path using **Dijkstra's algorithm**. 
After obtaining shortest path in the transformed image, it is again transformed to its original view angle and showed in "ARENA" window.
 
#
**How to run the program:** 

Run the path_finding.py file. 
"ARENA" and "solution_img" windows will appear. 
Using mouse **left click** select any point on line as **_start point_** and **right click** for **_end point_** in the "ARENA" window. 
Square will be marked at the start point and circle at the end point. 
Shortest path will be highlighted in **green**. 
Now, different start and end points can also be selected. 
Press enter to change the image in window "ARENA" and "q" to exit. 

#
IDE used is JetBrains PyCharm Community Edition 2019.2.5 x64

#
Images used are taken from Google Chrome

#


https://user-images.githubusercontent.com/50135239/130197586-e792390f-2f31-4c13-8470-43a35f5f5b33.mp4


