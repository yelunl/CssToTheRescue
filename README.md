# CssToTheRescue

## Week 1
First week I had to choose one out of 4 subjects to focus on during the next few weeks. I was in between fireworks and control panel. I chose control panel, then you have more freedom in what to make. I started to thinking about what the control panel should control. I wanted to choose something with 3D since i never done anything with 3D i want to learn how to work with that. I Sketched my first idea on paper. 

!PICTURE HERE!

I want to create a 3D cube and use the control panel to control things like speed and add more cubes and more. I still need to think of all the functionalities the control panel can do. Also need to add more controls for the control panel. 

## Week 2
Second week I started continuing thinking about the control panel. I decided to create a game console like the Nintendo DS. With the console I want to be able to control the cube. This week started writing the actual code and make the Nintendo DS. I used this picture as example.:

!PICTURE REAL NINTENDO HERE!

Creating the D-pad was the hardest thing about the Nintendo DS. I used the example that Sanne made and it worked. On all the buttons on the DS I used the button element.

By the end of the week I finished the Nintendo DS. And it looked like this.

!PICTURE HERE!

Next week I want to start creating the cube and adding functionalities on the buttons. 

## Week 3
This week I created the cube in 3d. I used this source from [W3C 3d transforms](https://www.w3schools.com/css/css3_3dtransforms.asp) to understand the transform properties and practice with it for a bit to understand how it works. I couldn't make it work at first so I looked up this [source about creating a cube](https://3dtransforms.desandro.com/cube).
Eventually it worked.

After playing around with it for a while I wanted to animate the cube. I want it go across the screen of the Nintendo DS. I remember from the theme sessions during the introduction week that there was a way to animate an element to move it along a path. I read the source of that page about this 'motion path' and practiced with it for a while to understand it. After that i could make the cube move. 

!PICTURE HERE!

Next what I needed to do is use the buttons to control the cube. One of the functionalities I wanted to add was change the path of the cube when clicking on one of the buttons. I brainstormed the logic to make this work a whole day. I wanted to give the bottom screen all the options to change the animation. Using the left and right keys on the d-pad you can choose from many options. When clicking the 'A' button you choose that option to apply it on the cube in the top screen. I didn't know how to make this work so I settled with adding max 2 options in the bottom screen and using the left and right of choose and ply the option to the cube on the top screen. The other buttons on the right you can choose different functionalities to change the cube. 

Whenever one of the buttons on the right are clicked, new checkboxes and labels are replaced on the bottom screen by the old one to make each checkbox do something different. This way each functionality is also saved by the previous click. 

To start making this work, I had to change the html code from using button elements on the right to checkboxes and on the left labels. Changing the html and css took a while. Eventually it worked.

## Week 4
This week added 2 obligated functionalities: nesting and style queries. 
I nested things like the cube and and many before and after elements. For the style queries i looked at what border has the color purple meaning what checkbox is currently selected and give the div element a transform: scale(1.2) to make it slightly bigger. I also got rid of a few imperfections and gave each option in the bottom screen a image. I updated my readme and i finished my project.
