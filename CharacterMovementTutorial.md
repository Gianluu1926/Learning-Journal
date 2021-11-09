# Character Movement

This shows how to make a gameObject move up, down, left and right based on the user's input.

# 1. Player Moving

-Select the Third Person Player and add a character controller component and change the radius and height to this:

![image](https://user-images.githubusercontent.com/91954726/140928501-52c7ec8e-8764-4b2e-b046-19407f264242.png)

This will give us a nice character controller collider

# 2. Create a new script

-Start by adding another component called ThirdPersonMovement script

Get rid of the start function and let's reference the character controller:

![image](https://user-images.githubusercontent.com/91954726/140929949-3e8e9233-e0e7-4e87-bd2e-182ffac31a7b.png)

Then save and attach the Character Controller to the script under "controller"

# 3. Rotating

-Work in the script that we have previosly created and to fix the rotation of the player we need to take the direction and figure out how much we should rotate our player on the Y axis to point in that direction:

![image](https://user-images.githubusercontent.com/91954726/140931604-1c83df4a-5ce7-4972-84fb-e7ab2bbdd861.png)

Atan2 is a mathematical function that returns the angle between the x-axis and a vector starting at zero and terminating at X , Y

-Let's also smooth the rotating:

![image](https://user-images.githubusercontent.com/91954726/140932270-9a29f268-9659-444a-aef5-9ceceae34549.png)


