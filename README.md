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

The Team had multiple discussions through text and voice during this week to discuss the progress on QA and general project status. Overall, the team feels the Alpha process has gone well. Communication has been open, everyone is working on their assigned roles, and the tools chosen in Module Two (Discord and the Excel task tracker) are working. The main lessons are about consistency: matching software versions, testing together earlier, and updating the tracker more diligently. 
 
1. What went well in testing
    - Communication: Every teammate named it as a strength. Members share progress, flag problems quickly, and stay in contact.
    - Role ownership: Everyone has contributed to their own area (programming, level layout, main menu, and art), with only minor bumps.
2. How bugs were identified and corrected
    - Hands-on testing in Unreal: Walking through the levels and playing with the systems surfaced most issues. This is how the team found that the crypt map had no collision.
      - Additionally, testing was done on a call with the team to showcase where errors were found outside the documentation. This showed how the error could be replicated.
    - Version control: Frequent GitHub pulls and pushes kept files current and exposed miscommunication between team members' work.
    - Team discussion: Reporting problems to the group helped narrow down causes, including collision, file, and Unreal version issues.
3. What we would do differently
    - Standardize the Unreal version: Soon as we started trying to merge documents, we realized there were multiple versions being used across members. A discussion should be had from the start to ensure everyone is on the same version to avoid issues loading updates and merging git branches.
      - To correct this issue, a new repository was created. The programmer pushed the initial commit to main and the Team Lead took over migrating the other individual Unreal Engine projects into the main one. From there we created a working-branch and all updates were pushed to that branch.
    - Test everyone's work together earlier to catch integration issues sooner.
    - Clearer course expectations would have helped the team focus on the right areas. The PDF provided with project guidelines was extensive, but it seems the project does not require everything listed.
    - Stronger GitHub skills across the team, with more in-depth understanding.
4. Module Two tools that worked
    - Discord: Helps with sharing art references, asking questions, seeing everyone's progress, and staying in contact.
    - Excel task tracker: Keeps everyone focused on priorities, shows what remains, tracks what works and what doesn't, and lets members report completed work.
5. Tools or techniques that were not helpful
    - Challenges (not tool failures): 
      - Texturing models in Maya has been the most time-consuming task for the Artist, so the plan is to finish the needed models first (axe, saw blade, doors) and texture afterward.
      - The task tracker isn't always updated in real time, and the team wants to improve on that.
      - Busy weekday work schedules have limited availability for meetings and slowed some art progress. It also limited communication this week.
6. How the initial game design document analysis shaped our tools
    - Team discussion: An early group discussion divided the work by role and established how we would communicate.
    - Tool selection: The team agreed collectively on Discord for communication and Excel for tracking, as suggested by Tina after reviewing the design document. Both were seen as easy and effective.
    - Broad task goals: Tools built around high-level goals help keep the team from getting stuck on one thing or drifting off track.

## Module Five Project Log - Team Reflection and Alpha Release
1. What parts of the plan did the team perceive to go well in relation to the last stage evaluation?
  - The majority of planned mechanics had been added and seem to be working as expected: enemies were in place, swinging axe model created by our artist was in place with alternating animations, a boss was added with a ranged attack with an additional ability to reflect the damage back to them. Our programmer put in many hours this week to be sure that there was a playable experience available to the testers.

2. What parts of the plan did the team perceive to go wrong in relation to the last stage evaluation?
  - It was difficult to balance real life with project expectations and areas of the project were delayed because of that. Any bugs or fixes that were needed in what had been completed during the week were simple to adjust. There was some difficulty with widgets but the UI/UX role was able to figure things out and implement them successfully.

3. How were the previous evaluations integrated into this latest stage?
  - We reviewed the previous QA list and created a new list for Beta that included all of the same checks. From Alpha to Beta we changed the health bar implementation, so while it existed and passed in the Alpha, it needed updating in the Beta. We understood how to test different aspects of the game and provide actionable feedback. We also adjusted the QA doc by removing areas we knew could not achieve at this stage while also keeping on track with the proper gameplay mechanics required of us.

4. What would you do differently to improve the collaboration or development process?
  - It is difficult to meet more often during the week due to work and family commitments, but we would be more active and responsive to one another in chat, while also remembering to lean on one another for knowledge and support. 

5. Were there any tools or techniques that you did not find helpful in the success of your project development? Why?
  - The project tracker is not being used as often as we hoped. Having a more dedicated project tracking system where documents could be attached and easily identified, owners could be tagged, and comments and feedback easily accessible. 
