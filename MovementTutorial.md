# Character Movement

This shows how to make a gameObject move up, down, left and right based on the user's input.

# 1. Create a Scene

-Start by opening Unity and creating a 3D project.

-Create a new scene and call it "CharacterMovement"

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



# 2. Create a new script

-Start by creating a script and name it "Movement"

We are going to create a public float called "speed", save it and then we are going to attach the script to the 3D Object.

![image](https://user-images.githubusercontent.com/91954726/136017364-06b33349-3709-4591-8f64-9aaa2018da4a.png)

![image](https://user-images.githubusercontent.com/91954726/136018141-acccbe2f-e682-402f-8bbf-0f12d63f5eb1.png)



