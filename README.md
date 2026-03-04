# GDIM32 In-Class Activities
## W1
### Activity 1
Try to understand and commit to memory the structure and functions of the syntax by describing it to yourself, to others, etc. and ask others for help whenever needed. 
:3
### Activity 2
1. 10
2. 2 
3. In every frame, the print message method is called. The print message method calls the Debug.Log method that tells the console to display "hello world."
4. Monobehaviour
5. As soon as the code runs the print message method will be called with the argument input of 10. The print message method calls the Debug.Log method that tell the console to display the value of the parameter plus itself.
6. Argument - What the method called should operate using
7. The variable being accessed in the Update method is a type name, not the name of an actual variable.
8. It should be _playerTransform.
### Activity 3 
[Group Document](https://docs.google.com/document/d/1KhRQZLNVzs5TZGDPKFDH77RtlX_e1vGLo3YVHySjxfM/edit?tab=t.0)

## W2
### Activity 1 
<img width="772" height="618" alt="image" src="https://github.com/user-attachments/assets/1bf9195d-a2f3-4243-85b9-91e235a87fa0" />

### Activity 2 
[Github Commit](https://github.com/UCI-GDIM32-W25/mg2-prettypinkanteater/commit/82b8d83696f4a307705036e8a1b0d6098ba6b016)
Worked on canvas, player jump, and started a little of the GameController script.

## W3
### Activity 1-2
Partner name: Nicole Yang

### Activity 3
<img width="786" height="652" alt="image" src="https://github.com/user-attachments/assets/4c14b6b2-0048-4b96-bc32-1e0853b9dd3d" />

## W4
### Activity 0
Partner name: Nolan and Brendan 

### Activity 1
Game objects containing the locator component all have it removed except for one. This is because the code checks for other instances of the Locator class that are not itself when it is initialized. If they exist, they are destroyed.

### Activity 2
<img width="794" height="1030" alt="image" src="https://github.com/user-attachments/assets/46a669c1-4651-4adc-8179-f3882fb45b27" />

### Activity 3
I had to commit earlier than class end because my laptop is going to die :(
[Github Commit](https://github.com/prettypinkanteater/HW4/commit/f2a0cef22ee0c763b279bdd0c4216775e1250119)

## W5
### Activity 1
I think the design of these interface and abstract classes is decent but I am not sure I would use an abstract class for the Use() method for items. The bodies of the method in the child classes are relatively similar with the use of Debug.Log.
I would likely just make the Use() method a virtual one in a normal class so that it can be overwritten in child classes when things like damage are to be added.

### Activity 2 
Model Classes: Enemy Stats and ItemW5

View Classes: Dialogue Bubble and Inventory UI

Controller Classes: EnemyW5 and PlayerW5

### Activity 3
#### Scenario 1:
Beats would be represented by prefabs that would have scriptable object containing the data like beat type, time, etc?

#### Scenario 2
The design patterns that would apply best to the situation would be inheritence with polymorphism and FSMs. This is because the characters have shared animations that would be best stored as states. They also have shared attributes like health
and attack. The character attacks can be overwritten in the child classes for unique distinctions between them. In terms of the different moves of movement/different attacks I think an abstract class would be best because there can be shared base methods and uniquely implemented methods.
Gameplay model manages doing damage.

#### Scenario 3:
State machines for player actionrs or animations.

### Activity 4
Attendance: Nolan Lovret Burns, Audrey Hu, Brendan William Johnston

Proposal: [Final Project Proposal First Draft](https://docs.google.com/document/d/1ol46riGsVF4tNG4s7EXD49n7NhyEQPBzmpgfhnkQLt8/edit?tab=t.0#heading=h.z11tcjvn40dh)

## W6
### Activity 1

#### Merge

- I already took notes on my own time and did not realize we needed to for this weeks in-class activity so nothing new for this catagory.
- Helpful for my project if my partners and I accidentally edit the same lines 

#### Performance Profiling

- Performance profiling can be viewed in Unity to show how long it is taking for methods to be called
- This would be helpful in my final project if we experience lag and want to determine the source

#### Gizmos

- Gizmos can be used to draw an object's collider to better visualize it
- If you implement the method in a class that is not for a specific game object, you can attach the class/script to multiple objects as long as they have the same type of collider
- This might be helpful in my final project for showing velocity to track player movement in the scene

#### Breakpoints
Thank you Professor Reid. 
- Show chain of events up until the method we are examining in call stack
- This is helpful for general debugging to check if methods we have written are actually being called or not in our final project and also the timeline of methods as well as events called/invoked to ensure that the logic runs sequentially accurate in quests and when players take actions


### Activity 2 
Attendance: Audrey Hu, Nolan Burns, Brendan Johnston

Final Proposal: [Final Project Final Proposal](https://docs.google.com/document/d/1ol46riGsVF4tNG4s7EXD49n7NhyEQPBzmpgfhnkQLt8/edit?usp=sharing)

## W7
### Activity 1
- Raycasting works well with NPC state machines because the criteria for changing states is based on NPC line of sight and if the player is in it, which can be tracked by Raycast arrows!
- Sphere casting can be used to read obstacle volume
- Save vectors as member variables for use with Gizmos
- Hitinfo is a variable containing which GameObject is hit
- Raycast hit returns a boolean based on if something is hit or not

### Activity 2
Attendance: Brendan Johnston, Nolan Burns, Audrey Hu :3

### Activity 3
<img width="1938" height="1006" alt="image" src="https://github.com/user-attachments/assets/98438422-0094-4ed1-9062-77540fc8a1e3" />


### Activity 4
[Trello](https://trello.com/invite/b/6995221d29a759665cbca1a0/ATTI3f505597092d3b79f0dfa0bab1504bbb292A9F57/gdim-32-final)

### Activity 5
[Git Commit](https://github.com/prettypinkanteater/GDIM32-Final/commit/e8b67b4cc3c49fcaba48103c76124e2d6611fc3c)

I sourced the sizzling sound effect and made a new script for controlling audio. I also setup things in Unity (assets folders) for organizing our work.

## W8
### Activity 1
#### Rendering Pipeline
- Rendering pipeline is cpu code for how EVERYTHING is rendered
- specific rendering pipelines also determine shader library
- cpu trades resources with gpu
- multiple options for rendering pipeline, make sure assets work with specific one using
- if an asset is built with a diff unity version than what you use, it will be incompatible

#### Post-Processing
- shaders that affect look of entire screen, can make game slow
- runs after rendering pipeline draws things in frame on screen (post)
- make game object and add post processing components!
- some effects may not be compatible with build type, test to determine

### Activity 2
Attendance: Brendan Johnston, Nolan Burns, Audrey Hu :3

### Activity 3
- slow movement
- Finish rest of the quest
- Colliders seem fine
- Bug with climbing on manager
- Likes animations
- Smooth  movement
- Knife phasing through things
- Fix outside, take away walls

### Activity 4
Fixing knife direction when picked up.

### Activity 5
[Git Commit](https://github.com/prettypinkanteater/GDIM32-Final/commit/60ac0b38123b415f0ee436d8d28d0cf32033ead7#diff-100a9f54f7867e743521c49a355002ada8aee0177e74900ffe5a8610d03f70a8)

My laptop was low battery so Brenden and I pair programmed and figured out a solution that I will work on this week outside of class.

## W6
### Activity 1
Scaling Well = easy for other users, programmers/content creators, to add data

Code architecture scaling well is crucial for building any game

Scaling is also a valuable skill for future employers

Scaling relates to the programming design patterns we learned because they contribute to architecture that scales well. (e.g. decoupling w/ singleton makes code more easily changable for data expansion,
state machines contribute to good scaling systems)

Branching dialogue should not be infinitely loopable, will lead to end dialogue node

If you have multiple talking NPCS would need invidiual dialogue controller class that would keep track of which npc is talking by setting active dialogue node to node that is talking
	- use method to change so that it can be called by other classes....

### Activity 2
Attendance: Brendan Johnston, Nolan Burns, Audrey Hu :3

### Activity 3
#### Goals: 
Does the manager have acceptable colliders 
Is the sensitivity and movement good

#### Feedback:
UI looks good!!!
A little unclear to get the potato first
Mouse sensitivity still high
Controls are smooth
Counter collider could be slightly larger
You can fit between the machines

### Activity 4






