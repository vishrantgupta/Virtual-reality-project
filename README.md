# CSCI559 Assignment04 - *One Last Dance* **Due: 03/08/2018** 

In this assignment you will start with the github classroom link, create your own assignment repository, clone it on to your computer, make modifications to the unity project, commit the changes, and push back the updated repository to github.

## Potential Resources:

- [VRTK - Virtual Reality Toolkit Website](https://vrtoolkit.readme.io)
- [VRTK - Virtual Reality Toolkit Documentation](https://vrtoolkit.readme.io/docs)
- [VRTK - Virtual Reality Toolkit YouTube Channel](https://www.youtube.com/channel/UCWRk-LEMUNoZxUmY1wO7DBQ)

- [VRTK - Pointers, Teleporting, and Object Interactions](https://youtu.be/sW9lxEUXfe8)
- [VRTK - Teleporting Tutorial(s)] (https://youtu.be/2IWAwFDhX2M) - There are multiple videos in series.
- [VRTK- Locomotion Tutorial(s)] (https://youtu.be/1rtXMzc2mfI) - There are multiple videos in series.

You should also feel free to watch anything else you find helpful, post to slack if you find good videos/tutorials/websites.

## Learning Outcomes
- You will learn about navigation by means other than the physical moving. In assignment03 you were able to move your user within the simulator by using the AWSD keys which simulated walking and via the mouse to simulate looking around the scene.  
- You will learn the ability to grab objects and move them within your scene.

## Directions
In order to receive full credit for the assignment you must do at minimum the steps outlined below, you may do more and explore other features within Unity and VRTK, in fact you are encouraged to do so as it will better prepare you for the two projects coming up in the second half of the semester.

### Required Steps
1. Clone the github repository to your desktop.
2. Modify the scene:
	- Add alternative form of movement beyond physical movement (e.g. move in the direction the controller is pointing when a button is pressed, move in the direction the user is looking when a button is pressed, use a teleporter).
	- Add a `Box Collider` to the table so user and objects don't go through it.
	- Add a `Rigidbody` component to the mug.
	- Add a `Capsule Collider` to the mug.
	- Add a `VRTK_InteractableObject` script to the mug object, and check the `Is Grabbable` checkbox.
	- Change the `Touch Highlight Color` to something the user can easily identify.
3. Commit changes to repository, remember to add a useful commit message(s).
4. Push committed changes to github.
