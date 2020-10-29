

 * Author : Logothetis Fragkoulis 
 * ECE
 * Electrical and Computer Engineer 
 

## Introduction 

The task is to create a realistic 3D Bowling game, using the Unity3D Game Engine. Initially, the scene of the game was implemented. Especially by using cubes floor, the walls and the whole arena were created. Then for each of the objects in the scene was given a Physic Material, Texture, Colliders:
1. The floor had to have almost zero friction, so the Dynamic friction was set to zero.
2. The ball should be able to slip easily on the floor, so its friction on the floor was kept low.
3. All the objects have its own textures and physic material and settings like (Light Emission) were adjusted.
When the stage architecture was completed, code scripts  were created to give life to the scene. Scripts were written  for throwing the ball, moving the camera (virtual player), UI’s, Audio Source , Score Projection , Restoring Pins and Ball, etc.
Then on the scene in Screen Space mode UI's were placed to show the current frame and the two-player Score.
Of course, the sound could not be missed from the game. A plenty of  sounds are played during ball slips on the floor, during the collision of the ball with the pins. Furthermore there is background music.
Finally, after all the basic steps were completed, a menu of options was designed.



## The Role of the Scripts 

*	Audio_Play.cs

It controls when the sounds will be played . 

*	Back_to_menu.cs

When player pushes ‘Esc’ and ‘Back to Menu’, it returns back to menu.

*	Final1.cs 

Pause scence (View the Score and Back to Menu choice).

*	Lancer Ball.cs  

Gives force, torque to the ball, and reset.

*	Menu.cs

Menu sections.

*	Move.cs

Control translation and rotation of the camera (virtual bowling player).

*	ResetBall.cs 

Trigger interface to reset the ball.

*	ResetPins.cs

Trigger interface to reset Pins.

*	Score.cs  

Full algorithm to calculate the current score, switch player, and etch.

*	ScoreManager.cs  

Controls UI’s - Score display.

Unity Prefabs 

Each pin behaves in the same way. So I included all pins in a Prefab. Consequently, all pins have the same RigidBody, Texture, Mass, Script .

Character
I built my own Character. 
I didn’t use Unity’s FPS Controller. (Move.cs)


# Play the game 
 Downlaod .exe file and double-click on it

