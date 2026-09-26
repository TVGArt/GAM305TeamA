# Team A Repository
## Team Members and Roles  
John Smith : Level Designer/World Builder  
Tina Velez-Grey : Team Lead, Lore  
Jennifer Beltran : Artist  
Justin Bass : Programmer  
Sophie Nolin : UI/UX Programmer/Designer  

### Team Roles Explained
Team Lead: This team member will oversee the repository and ensuring all required team documentation has been completed.  
Artist: This team member will oversee the aesthetics of the game.  
Programmer: This team member will oversee the base programming of the game (AI, Player, Mechanics).  
UI/UX Programmer/Designer: This role will oversee the UI/UX development.  
Level Designer/World Builder: This role will oversee the overall level design.  

## Module Two Team Project Plan
Engine: Unreal Engine  
Chosen Scenario: Top Down  

### Game 
- Starting Location: Player spawns inside a crypt/coffin
- Level Goal: The player goal is to get to a supreme human that is guarded nearby. They are of a royal bloodline such as Hellsing.    
- Storyline: WIP  
  - The player is a vampire that wakes in a crypt and seeks to drain the human that is being guarded. They will have to get through multiple rooms, each of which contains a piece of a key to open the door to the human.  
- Elements  
  - Player Power-up Pickups:  
    - Blood Vial  
    - Bandages  
    - Transformation Potion  
      - Researching options for bat, rat, mist, invisibility  
  - Enemies (Moving):  
    - Wandering Guards  
    - Rats or other animal type  
  - Obstacles (Moving):  
    - Swinging Axes  
    - Spike traps: popping out of the walls or floor  
    - Saw blades running across ground  
  - Obstacles (Traps):  
    - False floor/spikes at bottom of hole  
    - Pressure plate with dart or arrow attacks  

### Timeline
- 9/14:
  - Level Designer, Artist, and Programmer will research 2D vs 3D options and determine which type of art they prefer  
  - Artist will present concept art  
  - UI/UX and Artist will communicate on art styles to be sure that art styles are balanced  
- Alpha version will be completed by end of Week 4 (9/26)  
- Alpha minimum viable product:  
 - Alpha should have art consistent with fast prototype styles - basic shapes and models  
  - Programming  
    - Player Character:  
      - Movement, pickups, health increases/decreases on proper interaction  
    - Moving Enemies:  
      - Enemies that wander  
    - Moving obstacles:  
      - Swinging obstacle with collision/damage dealing  
  - Level design:  
    - Plans and layout for 5 rooms  
  - Artist:  
    - Player character design  
    - Level art  
    - item drop art
  - UI/UX/GUI:
    - Main Menu functionality: play game button, credits button
- Beta minimum viable product:
  - Player character takes and gives damage
  - Player picks up items and effects are properly applied
  - Enemies sense and attack player
  - Obstacles affect character and are appropriately animated
  - Main menu functions
  - Pause menu functions
  - Rooms build out and traversable

### Team Communication
- Main communication will be done through Discord chats and calls with information also being sent through email for easy access
- Twice a week, the team will meet in a Discord call. The first weekly meeting is to discuss progress and the following week's sprint goals. The second meeting is to discuss progress on that week's sprint as well as coordinate on assignment submissions.
- Project and task status will be reported in a shared excel document as well as the tice weekly meetings.

## Module Three Project Log - Team Development: QA and Testing Plan

[Sharepoint Excel Document with project tracker and QA checklist](https://snhu-my.sharepoint.com/:x:/r/personal/tina_velezgrey_snhu_edu/Documents/GAM305%20Game%20Task%20Tracker.xlsx?d=wc4c6406d56034a7c963e90a01b0c5bdd&csf=1&web=1&e=O71Q08)

### Testing Steps
- Play Test: Testing during the preproduction stage
- Demo: Testing before marketing will demo the project
- Code Release: Checking the code release demo with the test plan

### What items will be tested?
- Player Character:
  - on damage taken, health is reduced
  - attacks enemies and does damage
  - on character death, respawns to recent checkpoint (to be discussed)
- Enemies: 
  - enemies wander when not interacting with player character
  - enemy triggered by player character
  - enemy causes damage on attack
  - enemy takes damage on player attacking
  - on enemy death, enemy despawns
- Traps:
  -  pre-animated or can be triggered to animate
  -  On collision with player, causes damage
- Environment
  - Collectable items
    - keys: can be collected by player and are removed from scene on interaction
    - items: same as keys + effects are applied to player as expected on item use
    - Boss door: will not open without all 5 pieces of the key

### How will the test plan be updated to reflect changes to the game and design document?
As new items are added to the list, the date it was added will be added in the appropriate column. If there are areas that need different testing than what is posted, the no longer needed test will be marked with a strike through the words and a note added to explain why it is not being done

### How will bugs be reported?
The team will the 'Issues' feature available to us in github. When a new bug is found, the person who discovered the issue will create an issue before messaging the team as a group to let everyone know that a bug has been found and needs reviewed. This allows for a running history of issues and will allow for identifying ownership of responsibilities and the project success.

### How will the bugs and their changes be tracked over time?
As mentioned above, the bugs will be recorded in github under issues. We will also have access to discord historical messages. If the issue tracker does not meet the needs of the team, a separate excel tracker will be created to provide an easily accessible area for listing. Similar to the QA changes, as an issue is resolved, the line will be struck through, and a note added by the person making the fixes or determining the bug to not be an issue.

## Module Four Project Log - Team Reflection and Alpha Release
