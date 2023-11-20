# Tool Learning Log

Tool: **Babylon.js**

Project: **Interactive game**

---

10/23/23:
In babylon.js I started reading the documentation as well as going along with it. While reading the documentaion I had another tab open where I could edit the demo code and it basically explained to me what was supposed to happen. For instamce the code
  ```
  / Our built-in 'sphere' shape.
  var sphere = BABYLON.MeshBuilder.CreateSphere("sphere", {diameter: 2, segments: 32}, scene);

  // Move the sphere upward 1/2 its height
  sphere.position.y = 1;

  ```
when deleted would just get rid of the sphere.

  ```
  let groundTexture = new BABYLON.Texture(Assets.textures.checkerboard_basecolor_png.rootUrl, scene);
  groundMaterial.diffuseTexture = groundTexture;

  ```
this would change the color of the platform but not just the color but also give it patterns.
I also learned that I could basically save most of my projects on github which is useful to know as for other tools you have to save it directly to your computer.

https://doc.babylonjs.com/journey/theFirstStep

10/24/23:
Today I just looked at their demos and although they all look really cool because they're all sort of 3D and some are first person point of view, they however are not the type of game that I would like to make. I tried all the demos out to see if anything caught my eye or if anything seemed similar to what I wanted to make but nothing did. Although there was one game that had the option to talk to others but still not quite what I want. Tomorrow I will look at Gdevelop.


10/27/23:
After looking at the games made with Gdevelop, they look more like the games I want to make. Gdevelop has a few mini tutorials where you learn how to add joysticks, health bar, 3D objects, and much more. I did the first 6, they were all around 1-2 minutes. The two that I found the most intersting was adding a 3D object and improving the background so that it moves when the character is moving.
When adding 3D blocks to the project, everything was already made I just had to add a platform for the player to stand on. When I previewed it, it looked really cool because the block was 3D but so was the character.
To get the background to move when the character is moving, I had to set the behavior of the background layer. I set the background to CameraCenterX()/8 and CameraCenterX()/3 to get the background to move while the character moves too. I found this very cool because I put a background and then I put an image of houses on top of the background which made it look like the houses were moving too. https://editor.gdevelop.io/
Tomorrow I will do the next tutorials.


10/28/23:
Today I did the 3 part tutorials which were about 10-15 minutes.
The first tutorial was 5 minutes I basically added my own background and onjects of my choice. I Had to add a draggable extension in order to allow the user to be able to drag the object around. I also had to add behaviors to each of the objects to be able to get the to move. In the second tutroial I was able to add text to the screen and add trees on top of the original background to make it look like they were always there. The 3 part tutorial is all connected together. In roder to go onto the next one you have to finish the first. In the last part we add a start screen and a timer which is something I had already learned in the 2 minute tutorial. The next thing I am going to try is to see if I can make it so I could interact with other charcters in the game. For instance see little chat bubble on thier head and click on them to say something else.

11/13/23:
Today I went through the GDevelop documentaion specifically looking for something that would help me get the interactive part of the game that I want to create. In animal crossing you sort of have to inteact with the other characters to know what to do. The characters have little speech bubbles that have text appear as they speak and you can either click on it to skip to the end of what they're saying or you can wait until they're done talking. I don't reall know what this would be called but I'm assuming that it would be found under the `text` or `speech` documentaion. I found `auto typing animation for text "typewriter" effect ` that basically does what I explained above. It doesn't say if this would already show the speech bubble but I'm assuming that the speech bubble would be made seperately.


11/15/23
Today I went through the GDevelop documentaion to look for actions that could be added to the scene. `CurrentSceneName()` is used when you want the user to quit, pause, start or change the game. Which is kinda helpful how one expression can do so much. If the scene is going to be 3D, there is a variety of expressions that can be used,  depending on where we want the camera to rotate. For instance, if we want the camera to rotate towards tge X-axis we would input `Scene3D::CameraRotationX(layer name, number)`  or if it wanted to be roatted towards the Y- axis it would be the same expect the X would change to a Y and etc.



11/16/23
I want to make my game 3D, therefore, I've been looking at the documentaion for 3D gmodels instead of 2D because they use different file format. Which is actually very important to know, otherwise it would not have worked. 3D models are saved in .glb format and if I want to add lighting I have to add it through layers effects. Which basically adds effects to objects. There's also `global objects` that are useable by all scences but this can't be undone. But this would be helpful when I dont want to make a same object for every scence, I could just do it once.Once I finish finding enough expressions that I want added into my game, I will start tinkering with a game template while also adding those expressions. So far I will be tinkering with what I have found so far but defenielty with the auto- typing animation because that's what I want the most.
<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
