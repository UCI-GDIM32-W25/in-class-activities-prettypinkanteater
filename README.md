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

## W2
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