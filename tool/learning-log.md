# Tool Learning Log

Tool: **Unreal Engine**

Project: **Story game**

---

10/29/23:
* Finding materials and setting up UE
* [Unreal Engine's starter course](https://dev.epicgames.com/community/learning/courses/3ke/your-first-hour-in-unreal-engine-5-2/vvdk/your-first-hour-in-unreal-engine-5-2-overview)
* [A begining tutorial](https://www.youtube.com/watch?v=LeY6tAP-qss)

11/5/23:
* Using the video begining tutorial I loosely followed the tutorial. The main goal was to learn the basics and end up with a small level consisting of a fully modeled house.
* I learned that static meshes mean 3D models
* I started by creating an atmosphere to give the level light. Using the enviroment light mixer I followed instructions closely but then started to change up the lighting and colors of the level to make it look like a sunset.
* I followed the tutorial closely for the next while. I figured out how to further edit models and create more to a model using a grid. I eventually ended up with a starting platform with a path leading to another large platform. ALong the path I used a corner mode to select the corners of the path blocks I wanted to adjust and made inclines and declines along the path. 

11/6/23:
* I made the base house. In this part of following the tutorial I changed up a big part. In the tutorial they showed how to make a 1 story house, however to challenge my skills I decided to make a 2 story house with a set of stairs to the 2nd floor
* Started by using starting meshes for the walls and learned how to alt+click to duplicate meshes. Then I added stairs which there was already a preset for so I just had to increase the number of steps.
* I originally went to go make the 2nd floor by creating one box to model, then duplicating it to make the other part of the floor, except the 2nd part of the floor would be smaller so that there would be room for the player to go up with the stairs. However this didn't work because when I duplicated the modeled floor and went to go change some properties, when I changed the new box it changed the old one.
* I couldn't use multiple sections for the 2nd floor so I thought of an alternative. I decided I would use one modeled box for the floor and then make a space where the stairs could acess the 2nd floor. My first attempt seemed promising as I had used "cut face" to seperate a section of the floor from the main section. After I cut a strip of the floor I "disconnected" it and was able to move it as if it was it's own mesh and pushed it back til there was a hole for the stairs. However when actually testing the hole wasn't there
* I had a suspicion that there technically wasn't an actual hole in the mesh that the player could go through and it was confirmed when I selected the floor. From there I undid what I tried and started again by modeling the box for the floor and making it cover up to every wall. Then instead of cutting the face of the box I selected, I used "Poly cut" to cut and actual part out of the mesh which would prevent any collisions. This ended up solving my issue
* I carried on with the tutorial after making the 2nd story and then learned how to add materials/textures to the meshes which I decided to change up and personalize
<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
