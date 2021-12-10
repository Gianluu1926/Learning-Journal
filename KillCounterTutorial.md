# Kill Counter

This tutorial shows how to add a kill counter function to your game.

# 1. Create UI 

-Create a simple UI Text in your canvas

-Place your text where you most like it and make the text say "0"

-Edit the text to your preferred settings

# 2. Create a new script

-Create a new script and name it "KillCounter"

-Use the "using.UnityEngine.UI"

-Create a static int and name it "kills". And also create a public Text and name it "counterText"

# 3. Create voids

-create and name the private void "ShowKills()"

-Create and name the public void "AddKill()"

-Call the text counter in the update

![image](https://user-images.githubusercontent.com/91954726/145614464-0c888bca-a282-42e0-a594-582761f73be6.png)

# 4. Open the enemy script

-Create a variable for the kill counter called "killCounterScript"

-In the start function we are going to find for a gameobject called "KCO"

![image](https://user-images.githubusercontent.com/91954726/145614761-8905e982-6b60-453c-8119-f3f794f00c54.png)

-Finally increase the number of kills when you kill an enemy by adding this line:

![image](https://user-images.githubusercontent.com/91954726/145614940-f99641f8-e4c3-4ced-996a-9e044ac314dc.png)

# 5. Back to Unity

-Create an empty object and call it "KCO"

-Attach the kill counter script and assign the text to it

-Now have fun killing enemies and keeping the score!

