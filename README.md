# Recycl.it

A mobile accessible web application around the tracking of where people have spotted garbage and a community effort to reduce waste impact. A user can take a picture of litter and the application will post that image according to the location it was taken at onto a map where every user can see. The AI will classify what type of garbage it is by scanning the image it received. The user can additionally decide to create or join a cleaning party to help reduce waste impact along with other community members. Actions will be rewarded with points that can be redeemed for prizes/gifts from vendors.

Recycl.it was built on a backend based on Python, and Flask, with a Machine Learning layer using TensorFlow. This software uses flask to interact with the server, along with python to interact with various functions throughout the website. A Mask R-CNN was used to analyze and predict the types of trash found in an image. The frontend of the website was done using HTML5, CSS, AnimeJS, and Bootstrap. For map data and points on the map, we used MapBoxGL. This was connected through Javascript to the main website.

![Screenshot 2022-12-12 191037](https://user-images.githubusercontent.com/32677397/207190678-dba2aeb6-a9b9-4a3c-bd9d-e28ef3e04c45.png)

