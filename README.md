Design and make web-based VR rooms with AFrame
---
[**LIVE DEMO** ](https://chaupmcs.github.io/aframe_vr_room/)

#### Click the image below to watch a short video demo.
[![ScreenShot](/screenshots/beginning_scene.png)](https://www.youtube.com/watch?v=JHhUk9zAGJ0&t)


This is a basic web-based VR application that allows you to navigate through a decorated house and interact with some objects in it. 
The application was created by [A-Frame framework](https://aframe.io/).

The following screenshots highlight some of the features/components of the house.

## Interactions/Animations
1. **Cat**: Hover the cat to see the text. When clicking on the cat to suggle it, you will hear the meows.
The mouse hover is done by *AFRAME.registerComponent("name-on-hover")", and the audio is binded to the cat with *sound="src:#cat_meow; on: click"*
![pet_me](/screenshots/pet_me.gif)


2. **The TV**: Click on the TV to toggle it. While on, the TV displays an image and plays a song. Click on the TV again to turn it off (black screen).
![TV](/screenshots/TV.gif)


3. **Teleport upstairs/downstairs**: To go up/downstairs, use the teleport buttons near the stairs. 
It will change the position and rotation of the camera to move us go up/downstairs. 
![teleport_up](/screenshots/teleport_up.gif)
![teleport_down](/screenshots/teleport_down.gif)


4. **Time machine**: Click on the rail switch to turn back time, when there's no COVID19. 
Back then, we can have friends come over for a small party in the house. 
However, many things changed when the virus attacked. 
Not only no more parties up there, but these changes are reflected in the living room and working room as well. 
For example, the toy car and the cat show up in the present only. Perhaps, these things help us to overcome the quarantine while stuck indoors.
The bookshelf changes its position too. It was from the working room but later moved out to the living room, next to the TV.
![time_machine](/screenshots/time_machine.gif)

5. **Toy car**: The car is running by changing its *position* attribute via *<a-animation>*.
![toy_car](/screenshots/toy_car.gif)


6. **Ceiling fan**: Similar to the above-mentioned toy, but this time with *rotation* attribute.
![fan](/screenshots/fan.gif)


## Models:
Fan: https://sketchfab.com/3d-models/ceiling-fan-lp-20026b96c5144e5b923f1c8c4f8d41e7

## REFERENCES
- 3D models\
[1] https://sketchfab.com/\
[2] https://free3d.com/free-3d-models/
[3] https://clara.io/
[4] https://grabcad.com/
[5] https://www.cgtrader.com/
[6] https://poly.google.com/
[7] https://3dwarehouse.sketchup.com/


(to be updated...)
