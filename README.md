# GDIM 33 In-Class Activities
## W1
### Activity 1
[MiroBoard](https://miro.com/app/board/uXjVGoFOVg0=/)

1. Almost every image I chose is tropical or beach-related, with Hawaii showing up specifically multiple times, which tells me I'm drawn to a particular island vibe rather than just a generic sunny setting. The two games I picked, Super Mario Sunshine and Coral Island, are both chill and exploration-focused, so I'm probably interested in something cozy and social, maybe co-op, that feels like hanging out rather than competing. The jungle sci-fi image is the odd one out, but I think it means I still want some adventure or conflict underneath the relaxed surface, like how Sunshine has a villain plot set on a vacation island.
2. My personal interests and my partner's are actually really similar, which I think is cool because it kind of happened naturally. We both love nature, the beach, and sports.
3. My LA really like puzzle games and game with a gray color scheme with a concenete aesthetic. I also can agree with this, I think puzzle games are very engaging and entertaining. I think the concrete aesthetic, and I think I might get into it more. 

### Activity 2
1. I want to do a paper please like game.
2. Gameplay Loop:
- Each shift, a line of visitors approaches your booth one at a time.
- When an NPC steps up, you see their profile card on one side of the screen showing their listed traits like species, clearance level, physical description, and ID photo.
- On the other side you see the actual NPC standing there.
- You click different parts of the NPC to zoom in and inspect them, looking for anything that doesn't match their profile card
-  You then make a call: let them through or flag them as an anomaly.
-  After your shift ends, you get a score based on how many you got right.
-  Get too many wrong and you get fired.
2. Breakdown:
<img width="448" height="591" alt="Screenshot 2026-04-01 at 8 01 27 PM" src="https://github.com/user-attachments/assets/e3cdb0f1-cb46-4488-b492-e99ad7534c4f" />

 ## W2
### Activity 1
   <img width="1054" height="537" alt="Screenshot 2026-04-15 at 9 52 51 PM" src="https://github.com/user-attachments/assets/1da163c7-1adb-4241-8939-0d43b155c2ce" />

### Activity 2
#### Q1
This is because if we want to change the variable name, we only have to change it in one place. This string is a scene varabile which means it comes up on all the on=bjects in the scene.
#### Q2
I used the one in the explore state in the state machine in the explore state. This helped me know that the state machine was working specifcally if the penguin can move and the Dialogue ui showed up.
#### Q3
Set Cursor Lock State has high relvance to my game. Since my game is like a paper please like game, using this will prevent the mouse from drifting off screen. IN addition, it can manage high spped tasks such as inspecting the alien whille not going off screen or misclicking.
#### Q4
Game State has high relvance to my game. Since my game is like a paper please like game, the NPC or the aliens are going to be going through 3 game states: arriving for inspection, getting inverstigated by the player where they either get flagged or let through, and leaving the inspection.

## W4
### Activity #1
 1. My playable build has accpet/deny button, the score that updates, and it rotates with the sprite.
 2. My playesting goals is to make sure the button works, the score updates, and the sprites change.
 3. My playtest team is: Sonia, Andrew, Pinhsuan, and Rebecca.
 4. Here is my playtesting notes:
- one of the assest needs to be cropped better.
- score updates
- accept/deny works
- sprite changes
- better guidelines on scoring system: restricitons.
### Activity #2
1. Yes, a writer can add more lines of dialogue without writing code. This is because each dialogue node or option is a scriptable object that can duplicated. Ech scriptable object is tunable in the inspector because it has a serialized field. Because of this, all the writer has to do is to put the the lines of dialgoue they want in the inspector rather than coding it.
2. There is no limit to the amount of dialgoue nodes the writer can create. This is becuase scriptatble objects make diagloue systems very easy to scale.
3. Regenerating nodes updates the nodes library so visual scripting graphs can find scripts,custom nodes, and other changes. This is useful for the intial graph setup, script changes, and type option nodes (and the ones you can create in this also). 
## W5
### Activity 0:
My unity tool of choice is the Scriptable Objects. 
### Activity 1:


1. create Scriptable object
-create an asset menu so I can duplicate it in the inspector
- fill the information in code for what the scriptable object is going to hold including the spirite
- in the unity, create one scriptable object and fill in the inspector with the data you want
 2. create a list that iterates through all the aliens
- create a list and make in a new list
- set the currentIndex to 0 in awake
- update the current index and reset back to zero
- update the sprite image based on the scriptable object selected
3. hook up the scriptable objects in the inspector
- add this script to the object you want to add it to (alien ui image)
- open the list and attach the first scriptable object
-  use the plus button to add all you scriptable objects

### Activity 2:
- I implemented my scriptable object sprite to change
- I also set my game objects that were suppose to tbe active and deactivated them.
-  I also polished my state machine

## W6
### Activity #1
 1. My sprite rotates on exit, is what is new in my build from playtest one.
 2. Itch link: [My itch link](https://jedi-narwhal.itch.io/playtest2)
 3. My playesting goals is to make sure the spritie changes on exit gameloop is complete and any other feedback.
 4. Here is my playtesting notes:
 - unexpected flickering between sprites
 - confused about the text maybe make a object
### Activity #2
1. When you mutiply 2 decimals, the number becomes smaller. This gets you closer to zero which is darker and less saturated.
2. It will become more transculant because the numbers become smaller. This will get you closer to zero amd become more transculant.
3. The UV coordinates are stored is in the vertic data of the UV mesh of the shader.
4. Yes, this is really interesting to me. I thought is was really cool you can do this!

## W7
### Devlog Questions
1. The data from the Shiba Mesh.
2. It is blended at the edges because each vertex has a color going in between the vertices, the clor becomes interprolated.
3. It is less detail because we are using a vertex from the mesh which is less detailed than a texture. It helps artists know inconsistancies.
4. In the back hind leg, the color is off and there is a whole of a random color.
5. We could use the UV map becuase it will give us the colors will get applied to the mesh.
6. The surface normal on the shiba of the leg isn't perpendicular to the surface.
7. We use addative because we want to add the fire to whatever is behind it. By adding 2 colors, the colors increase and the value gets lighter.

## W8
### Activity #1
 1. I added a ui puttion to tell you where to click and i added an npc.
 2. Itch link: [My itch link](https://jedi-narwhal.itch.io/playtest3)
 3. My playesting goals is make sure this activates and deactivates during the player inspection phase. Make sure my game makes sense and is understandable for the player.
 4. Here is my playtesting notes:
 - polish UI
 - npc faster
 - adding more npcs
 - text concsise sentence
 - ui indicator poped up, but still stayed on after end screen
### Activity #2: The first one-I answered the questions at the end of the doc
1. The stencil buffer is used to mark where the original Shiba is drawn by writing a value of 1 to those pixels. Then, the outline pass only draws where the stencil value is not 1, so the enlarged mesh only shows around the outside of the object and creates the outline effect.
2. The Shiba gets drawn multiple times: once normally, once for the stencil pass, and once for the outline pass. This happens because each render feature needs its own pass to create the effect.
3. One way to improve the inefficiency would be combining some of the passes into one shader or reducing the number of objects using the effect. This would lower the number of extra draw calls.
4. DarkShadowAmount should mostly stay between 0 and 1 because the dot product values used for lighting are usually in that range.
5. We add the lighting sections together because the lit and shadowed areas are separate parts of the final image. If we multiplied them, parts of the texture could become too dark or disappear.
6. Changing the Shiba’s layer enables or disables the outline because the Renderer Feature is only set to affect objects on the Outline layer. If the object is moved off that layer, the outline pass ignores it.
7. Setting the shadow color to white removes the shading because multiplying colors by white keeps them the same. That means the “shadowed” parts no longer get darker.
8. Modifying materials at runtime can hurt performance because Unity creates separate material instances for objects. This uses more memory and can make rendering less efficient if a lot of objects do it.

## W9
### Activity #1: Rendering effect brainstorn
1. Our game we chose is Detroit We Come Human.
 <img width="2608" height="1265" alt="image" src="https://github.com/user-attachments/assets/1b9cb14a-5953-4a35-94f5-86881bca9408" />

 <img width="2405" height="1374" alt="image" src="https://github.com/user-attachments/assets/26a845a0-261c-4a62-a843-24decad28b06" />


2. Implementation Details:
   - change the rendering effect of the camera to turn down the saturation of everything
   - need to make a second shader, make it a material, then attach it to every interactable object. 
   - we need to code it to have a blue hue
   - then we need to code it to activate it when we are in "robot view"
   - then turn it off when it is in normal view (so we can view the effect)
     
### Activity #2: Shader Graph
1. One problem I solved today is having a thin shader outline. Before I had a background inverted the whole ui image, but I just wanted the sprite. So to do this, I coded the alpha threshold to 0.1 so it gets only one pixel of the background.
2. Shader Graph:

<img width="590" height="412" alt="Screenshot 2026-05-27 at 10 59 26 AM" src="https://github.com/user-attachments/assets/4ba2cdfc-af66-4296-9fbc-f64bd63144a7" />

