# Tool Learning Log

Tool: **Unreal Engine**

Project: **Story game**

---

10/29/23:
* Finding materials and setting up UE
* [Unreal Engine's starter course](https://dev.epicgames.com/community/learning/courses/3ke/your-first-hour-in-unreal-engine-5-2/vvdk/your-first-hour-in-unreal-engine-5-2-overview)
* [A begining tutorial](https://www.youtube.com/watch?v=LeY6tAP-qss)

11/5/23:
* I wanted to start off with the UE starting course but there was trouble loading the documentation when I went to go test so I'm starting with the tutorial video
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

11/12/23:
* I continued where I left off and I started making the interior look more lively with props however because there were no lights in the house it was too dark for me to see anything. However when skimming through the prop section of the tutorial I discovered you can change your viewport and put it in different modes. If I put my viewport as unlit, the area would light up and it would remove all shadows. This made my time from then on much easier because it allowed me to see the meshes more clearly.
* The first floor I just wanted to practice placing and positioning meshes from the content drawer. I wanted the first floor to be just many tables and chairs so I place a table and surrounded it with three chairs. Then I selected them all and duplicated the mesh a couple of times and made each group different to add variation.
* For the 2nd floor I wanted to be a bit more ambitious, I wanted to alter the meshes on the 2nd floor to make it look more unique. I wanted a longer round table surrouned by a few couches and chairs. I could have just used the scale tool but I wanted to test something out. Earlier I had problems with duplicating floor and trying to alter it to make the 2nd floor, but when making the roof I had to duplicate the roof by actually hitting a dupliate button which actually makes the mesh 100% seperate from the other meshes so that you can use poly edit without affecting the other meshes of the same prop. I duplicated a table "normally" and then went to the modeling menu to duplicate, then I used poly edit to stretch out the table to make it longer and I was able to do so without affecting the other tables downstairs. While I didn't do this with the other props on the 2nd floor, just using the scale tool, I still think this was useful to test and know.
* A quick thing to mention is that I learned the importance of saving frequently. After I finished adding lights initially I didn't save and wanted to just wanted to test to see how it all looked. However I did it too suddenly and it completely froze my pc and I had to reset it. As a result my progress on the lights was completely lost and I had to re-do it. REMEMBER TO SAVE OFTEN!
* I added lights to both floors and wanted the atmosphere to be different for both floors. I figured out how to add light sources and different types. For the main wall lights I used point lights and on the 2nd floor I placed two ceiling lamps. The first floor I used red lights and the second floor in contrast I used brighter, slightly blue, lights. This, along with the different use of props, created a different atmosphere between the two floors and that is something I believe is important.
  
<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
