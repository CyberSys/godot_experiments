# Godot experiments

Some of my 2D/3D/VR/UI experiments in Godot.

## Projects & descriptions

| Icon | Type   |  Tittle | Description | Status |
:-----:|:-------:|:-------:|:-----------:|:------:|
![](2D/hang/icon.png) | 2D | hang | you hang from a rope, swinging to reach the goal | DONE ✔
![](2D/mobile_ui/icon.png) | 2D | mobile_ui | trying the Godot's UI node on mobile | DONE ✔
![](2D/quick_prototype/icon.png)| 2D | quick_prototype | a small scene with a script to allow quick prototyping. You draw a shape with the line2D, and it automatically add a physics body and a background to your shape. | DONE ✔
![](2D/android_accelerometer/icon.png)| 2D | android_accelerometer | trying to use the accelerometer to set the gravity | DONE ✔
| | | | |
![](3D/car/icon.png) | 3D | car | a test with godot vehicle body physics and trial-like terrain | WIP 🛠
![](3D/plane/icon.png) | 3D | plane | plane controller | WIP 🛠
![](3D/procedural_animation/icon.png) | 3D | procedural_animation | prodecural animation of a spider-like (or robot) model, with inverse kinematics | WIP 🛠
![](3D/spectrum_analyzer/icon.png) | 3D | spectrum_analyzer | simple spectrum analyzer moving 3d objects | DONE ✔
![](3D/tv/icon.png) | 3D | tv | displaying a video or frames on a crt tv | DONE ✔
![](3D/wheelBot/icon.png) | 3D | wheelBot | a robot rolling on one wheel | WIP 🛠
![](3D/area_gravity/icon.png) | 3D | area_gravity | a simple test using the gravity of an area | DONE ✔
![](3D/android_maze_accelerometer/icon.png) | 3D | android_maze_accelerometer | control a maze's orientation with the phone's acceleromter | WIP 🛠
![](3D/robotic_arm/icon.png) | 3D | robotic_arm | computer vision + IK test with a robotic pick and place arm | WIP 🛠
| | | | |
![](VR/quest_playground/icon.png) | VR | quest_playground | a project testing various things in VR for the Oculus Quest: handtracking, handtrackings physics | WIP 🛠
![](VR/table_tennis/icon.png) | VR | table_tennis | trying to use Godot's physic to recreate a table tennis game | WIP 🛠
![](VR/bow_and_arrow/icon.png) | VR | bow_and_arrow | bow and arrow mechanic | WIP 🛠
![](VR/control_like_interaction/icon.png) | VR | control_like_interaction | trying to recreate CONTROL like movement, and messing with area's gravity | WIP 🛠
| | | | |
![](MISC/slow_down_sound/icon.png) | MISC | slow_down_sound | showcase an effect where the pitch and volume of the music is decreased with a tween. Useful for a "loosing" effect, when a player dies for example | DONE ✔

## Videos & GIFs

### Accelerometer android maze 3D

<img src="videos_gifs/accelerometer_android_maze.gif" width=400>

### Accelerometer android 2D

![](videos_gifs/android_accelerometer.gif)

### Area_gravity

![](videos_gifs/area_gravity.gif)

## Useful

- [3D/android_maze_acceloremeter]:
  - GLES2 was buggy for me, some texture were not shown
  - Bullet physics has a bug when you change the gravity vector at runtime -> use Godot physics instead

- [3D/robotic_arm]: 
  - GLES2 doesn't work correctly with IK, part of the mesh is not moved
  - Bullet physics' constant velocity for static body doesn't work -> use Godot physics instead
  - The IK target must be high in the tree than the SkeletonIK node, otherwise Godot freaks out

Icon background color: #022C4D

http://www.mazegenerator.net/

## About me

- [Twitter](https://twitter.com/VicMeunier) 
- [Sketchfab](https://sketchfab.com/victor.meunierpk)
- [Itch.io](https://mreliptik.itch.io/)

## LICENCE

- **2D/android_accelerometer**: (texture + balls) [Kenney](https://www.kenney.nl/)
- **3D/android_accelerometer**: (Ball + flag) [Kenney](https://www.kenney.nl/)