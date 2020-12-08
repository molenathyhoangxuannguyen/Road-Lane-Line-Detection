# Road Lane Line Detection – Computer Vision Project in Python and OpenCV

Sources: https://data-flair.training/blogs/

## Objective: 
Utilizing computer vision methods in Python, we are going distinguish street path lines in which independent cars must run. This will be a basic portion of independent cars, as the self-driving cars ought to not cross it’s path and ought to not go in inverse path to maintain a strategic distance from accidents.

To identify white markings within the lane, to begin with, we ought to veil the rest portion of the outline. We do this utilizing outline concealing. The outline is nothing but a NumPy cluster of picture pixel values. To cover the unnecessary pixel of the outline, we simply overhaul those pixel values to within the NumPy array. After making we got to identify path lines. The method utilized to distinguish numerical shapes like this can be called Hough Change. Hough change can identify shapes like rectangles, circles, triangles, and lines.

Path Line location could be a critical component for self driving cars additionally for computer vision in common. This concept is utilized to portray the way for self-driving cars and to avoid the risk of getting in another lane. In this article, we are going construct a machine learning venture to identify path lines in real-time. We are going do this utilizing the concepts of computer vision utilizing OpenCV library. To identify the path we got to distinguish the white markings on both sides on the path.

The lines drawn on the streets direct human drivers where the paths are. It also alludes to the heading to direct the vehicle. This application is cardinal for creating driverless cars.

