# Camera Movement

This shows how to set up a camera movement to follow the character.

# 1. Create a Scene

-Start by opening Unity and creating a 3D project.

-Create a new scene and call it "CameraMovement"

-Add a 3D object that you wish and name it "Character"

# 2. Editing the object

-Remove the collider by right clicking on it, since the object will just act as our graphic

-To have an idea of where the player would be facing direction let's create a cube object and scale it
so that's going to look like this:

![image](https://user-images.githubusercontent.com/91954726/136019590-9a9b10b8-7941-441a-becd-6dc62e3505d0.png)

This has been done so that now we know where the player is facing forward.

-Remove the collider from the cube too and make the cube child of the Character

-Now create a new gameObject and place it in the same position of our character by just making it child of it and resetting the transform and then drag it out again

-Now drag the Character into the gameObject and name it "third person player"

This has been done so that now we have separated the logic from the graphics

# 3. Using Cinemachine

Chinemachine is a easy to use plug in which give great game quality controls for every camera in your project.

-Go ahead and select the package manager in the window section and search for cinemachine and install it

-Now select the FreeLook Camera under Chinemachine and name it third person camera

This will tell what to do to our main camera and will follow the third person camera.

# 4. Setting up the camera

-Let's drag the Player object into the Follow and Look At section under the camera as shown:


so that now the camera will follow the player movements.

-Now let's adjust the camera under "orbits"

"Binding Mode" change it to World Space

"bottomRig" by decreasing the height to something like -1.60 and changing the radius to something like 12 

"MiddleRig" By increasing the height to something like 5 and changing the radius to something like 17

"TopRig" By increasing the height to something like 14 and changinng the radius to something like 12

Under the Y and X axis change the value to whatever you prefer the most 

This will allow the camera to be more distanciated from the player

![image](https://user-images.githubusercontent.com/91954726/140926946-5d388e46-de97-402b-ae35-a0a0249429d6.png)
