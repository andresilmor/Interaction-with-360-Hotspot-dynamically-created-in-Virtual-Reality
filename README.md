# Interaction with 360º Hotspot dynamically created in Virtual Reality

This exercise is an improvement of the exercise [[Interaction with 360º image elements
](https://github.com/andresilmor/Interaction-with-360-image-elements)] where an 360º image is mapped with "static" points of interest in which we can click and display more information about, NOW, instead of the mapping being maded in the Unity Editor and being "Static" the mapping is created on base of the information inserted on a JSON file, in which we can put the information to be displayed (text/image/video) and the location of the point of interest, with that said there's still a need to do a setup of the mapping on the Editor to get the position of the points of the interest, but after that information being writted down in JSON, the mapping can easelly be shared without the need of copying the project.

The goal, while not implemented yet, is to, instead of the mapping being retrieved from a JSON, to be retrieved by an API call with all the information, including the image itself, being saved on the Server-Side, in a way that the User/Developer just needs the basic version with the Prefabs and the dependencies. A goal with a little more challenges, is to instead of being needed a first setup of the points of interest in the Unity Editor (to retrive the position), an User/Developer should be able to create is own 360º Hotspot on a web application using a panoramic image and marking with just a mouse click.
