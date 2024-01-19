# Entry 2
##### 12/18/23 Learning GDevelop

### Introduction
 The freedom project is a long year project where you make anything of your choice. For this year's freedom project I decided to choose GDevelop as my tool. In my previous blog I talked about how I looked at the GDevelop documentation and started messing around with some of the behaviors/expressions. In this blog I'll go more in depth about how I started trying to make something that I actually want included into my game.

### GDevelop
##### Auto Typing:
 In GDevelop I went through the documentaion specifically looking for something that would help me get the interactive part of the game that I want to create. In animal crossing you sort of have to interact with the other characters to know what to do. The characters have little speech bubbles that have text appaear as they speak and you can either click on it to skip to the end of what they're saying or yoy can wait until they're done talking. As I was looking through the `text` and `speech` documentation I found `auto typing animation for text "typewriter" effect`. I added the autoptyping behavior to text. Before the text is displayed I inserted the text that I wanted printed out. When the text is being printed out it looks like it's being typed out as it's printed out. I chose the `text_autoTyping` and made the interval between characters in seconds, 0.05. The lower the number is the faster it's printed out and the higher the number is the slower it's printed out. Now I need to make it so that it doesn't appear throughput the whole game.

 <img width="444" alt="Screenshot 2024-01-18 at 11 24 10 PM" src="https://github.com/arianas4499/apcsa-freedom-project/assets/91750441/061ca9a0-395f-4956-92bb-39be9a5d5749">

Unfortunately, I was unable to include a video of how `text_autoTyping` works. However, as seen in the image above it is just text that is shown right next to the character but its displayed as if the person was typing it at that very momemnt.

##### Scene
I went through the GDevelop documentaion to look for actions that could be added to the scene. `CurrentSceneName()` is used when you want the user to quit, pause, start or change the game. Which is kinda interesting how one expression can do so much. I've tried incorporating the expressions for the `auto typigng`, such as; pause,skip, end and etc, howvever, it hasn't really wokred for me.  If the scene is going to be 3D, there is a variety of expressions that can be used,  depending on where we want the camera to rotate. For instance, if we want the camera to rotate towards tge X-axis we would input `Scene3D::CameraRotationX(layer name, number)` or if it wanted to be rotated towards the Y- axis it would be the same expect the X would change to a Y and etc.

I also want to make my game 3D, therefore, I've been looking at the documentaion for 3D models instead of 2D because they use different file format. Which is actually very important to know, otherwise it would not have worked. 3D models are saved in .glb format and if I want to add lighting I have to add it through layers effects. Which basically adds effects to objects.

There's also `global objects` that are useable by all scences but this can't be undone. But this would be helpful when I dont want to make a same object for every scence, I could just do it once.Once I finish finding enough expressions that I want added into my game, I will start tinkering with a game template while also adding those expressions. So far I will be tinkering with what I have found so far but defenielty with the auto- typing animation because that's what I want the most.

### EDP
I am currently on step 3 and 4 of the engineering design process because I'm still figuring out the documentaion and how to actaully use it, as well as how I want to use it in my game. Although, it has been a struggle to combine things in the documentaion to create something such as the `auto typing effect` with the expressions, but it will be neccessary for the next step where I will actually have to start creating the bare minimum for a working game.

### Skills
While going through the process of brainstorming possible solutions, I have learned how to learn and how to google. For instance, when I was really struggling with adding expressions into my object I googled how to use it and I got a website of information that seemed very useful. I also learned how to learn because the documentaion doesn't really explain how to use it so I've had to figure it out on my own and it defenitely has not been easy but worth it.

### Next Steps
My next steps are for sure to know how to incorporate expressions into my objects because that will help me achieve my goal. However, if I really don't understand how to do it by the end of when blog 3 is due then I will focus more on other things because I also need to create a working game. The `auto-typing effect` is just an extra thing that i would really like to add and I hope to accomplish. I will also have a look at ` https://wiki.gdevelop.io/gdevelop5/all-features/string-instructions/ ` because this has a good explanation of what I'm trying to achieve. 

[Previous](entry01.md) | [Next](entry03.md)

[Home](../README.md)
