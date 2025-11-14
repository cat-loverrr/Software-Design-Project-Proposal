# Software-Design-Project-Proposal


## Identifying and Defining:

### Identifying a Need: Think about a problem or need that your game or simulation will address. Clearly define this need.

- **Need:** To provide players with an engaging first-person shooter (FPS) experience that improves reaction time and strategic thinking whilst offering immersive entertainment.
- **Problem Statement:** Many FPS games focus only on fast-paced shooting without encouraging deeper skills like strategy. An FPS that combines action with tactical decision-making can help players develop these skills while keeping them entertained.
- **Skill Development:** To develop the skills in Unity required to create the game, I will follow along some tutorials sourced online to gain an understanding in what is being done during the project.

### Requirements Outline:

  - **Inputs:** *What inputs will your project require?*
    
    ***User inputs will include:***
    
     o W, A, S, D keys for character movement (forward, left, backward, right).
    
     o Mouse movement to control the camera view and aiming.
    
     o Left mouse click to fire weapons.

     o Right mouse click to aim down sights.
    
     o  Spacebar to jump.
    
     o Shift key to sprint.
    
     o  Ctrl key to crouch.
    
     o  R key to reload weapons.
    
     o  E key to interact with objects (open doors, pick up items).
    
   - **Processing:** *Describe the processing that needs to happen.*

      ***The processing for each input:***
     
      o The program will read the keyboard inputs (W, A, S, D, spacebar, etc.) and update the player’s movement direction and           position in the game world.

      o The program will process mouse movement to rotate the camera and aim the player’s weapon.

      o When the left mouse button is clicked, the program will trigger the shooting mechanic, check if bullets hit enemies,            and apply damage.

      o When the right mouse button is clicked, the program will adjust the camera field of view to simulate aiming down sights.

      o The program will check for collisions between the player, environment, and projectiles (e.g., walls, obstacles,                 enemies).

      o The program will calculate physics interactions such as gravity for jumping, crouching, or falling.

      o The program will update the HUD (Heads-Up Display) to show ammo count, health, and score whenever actions occur (like           reloading or taking damage).

      o The program will handle game logic such as switching weapons, interacting with objects, or triggering events when               certain inputs are pressed.
     
   - **Outputs:** *What outputs will your project produce?*

     o The game will update the screen display to show the player’s movement, aiming direction, and weapon firing.

     o Visual effects such as muzzle flashes, bullet impacts, explosions, and health bar changes will appear.

     o The HUD (Heads-Up Display) will show ammo count, health status, minimap, and score.

     o Sound effects will play for actions like shooting, reloading, footsteps, jumping, and taking damage.

     o Messages or prompts will appear for events such as “Reload,” “Objective Complete,” or “Game Over.”

     o Animations will update for player actions (running, crouching, jumping) and enemy reactions (hit, defeated).

     o The game will provide feedback through visual cues like red screen edges when the player is hurt
   - **Transmission:** *Will there be any data transmission requirements?*

     The game will not require any network communication or multiplayer support. All data, such as player progress, scores, and settings, will be stored and processed locally within          Unity.
   - **Storage:** *What data will need to be stored?*

     All the data that needs to be stored will be stored locally.

### Functional and Non-Functional Requirements: List and explain the functional (what the system should do) and non-functional (how the system should behave) requirements of your project.
 **Functional Requirements** *(What the system should do)*

**Player Movement**

- The player can move forward, backward, left, and right using keyboard inputs.

- The player can jump, crouch, and sprint.

**Camera & Aiming**

- Mouse movement controls the camera view and aiming direction.

- Right mouse click enables aiming down sights (ADS).

**Combat System**

- Left mouse click fires the equipped weapon.

- Weapons can be reloaded using the reload key.

- Enemy characters take damage when hit by bullets.

**Environment Interaction**

- The player can interact with objects (e.g., doors, pickups) using the interaction key.

- Collision detection ensures the player cannot walk through walls or obstacles.

**HUD & Feedback**

- Heads-Up Display shows health, ammo count, and score.

- Visual and audio feedback occurs for actions (gunfire, reloading, taking damage).

- Game-over and objective-complete messages are displayed when conditions are met.

**Game Logic**

- The system tracks player health and ends the game when health reaches zero.

- The game saves progress (levels completed, unlocked weapons) locally.

**Non Functional Requirements** *(How the system should behave)*

**Performance**

- The game should run smoothly at a consistent frame rate (e.g., 60 FPS) on target hardware.

- Loading times between levels should be minimal.

**Usability**

- Controls must be intuitive and responsive.

- The HUD should be easy to read and not clutter the screen.

- Menus and settings should be simple to navigate.

**Reliability**

- The game should not crash during normal play.

- Save/load functionality must work consistently to preserve player progress.

**Scalability**

- The game should allow for future expansion (e.g., new levels, weapons, or features) without major redesign.

**Maintainability**

- Code should be organized and documented so updates or bug fixes can be applied easily.

**Portability**

- The game should be able to run on different platforms (PC, possibly console) with minimal changes.

**Aesthetics**

- Graphics, sound, and animations should create an immersive atmosphere.

- Visual and audio feedback should enhance the player’s experience without overwhelming them.


### Social and Ethical Issues: Consider and analyse any social or ethical issues related to your proposed game or simulation. How will it impact users and society?

**Violence in Games**

*FPS games often involve shooting and combat, which can raise concerns about exposure to violent content. To address this, the game should avoid excessive gore and focus on strategy, skill, and story rather than glorifying violence.*

**Representation & Inclusivity**

*Characters, environments, and storylines should be designed to avoid stereotypes and promote diversity. This helps ensure the game is respectful and welcoming to a wide audience.*

**Addiction & Screen Time**

*FPS games can be highly engaging, which may lead to long play sessions. Including features like save points, pause options, and reminders can encourage healthy play habits.*

**Impact on Society**

*Positively, the game can improve reaction time, problem‑solving, and teamwork skills. Negatively, if not designed responsibly, it could reinforce aggressive behavior or reduce time spent on other activities.*

# Researching and Planning:


**Evaluation of Existing Ideas** 

Explore and evaluate existing games or simulations; How do they solve
problems? How do they balance mechanics, aesthetics, and usability?

*Do this in the form of a PMI (Plus, Minus, Implication) table.*

  | Game            | Plus (Strengths)                                                                 | Minus (Weaknesses)                                                           | Implication (Impact/Meaning)                                                                 |
|-----------------|----------------------------------------------------------------------------------|------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------|
| **Call of Duty** | - Cinematic campaigns with strong storytelling.<br>- Fast-paced, accessible gameplay.<br>- Huge multiplayer community. | - Annual releases can feel repetitive.<br>- Heavy focus on microtransactions.<br>- Can prioritize spectacle over innovation. | Keeps players engaged with polished mechanics and narrative, but risks fatigue and criticism for lack of originality. |
| **Halo** | - Iconic sci-fi setting and memorable characters.<br>- Balanced mix of campaign and multiplayer.<br>- Innovative mechanics (e.g., vehicles, energy shields). | - Some newer entries received mixed reviews.<br>- Multiplayer updates inconsistent.<br>- High learning curve for newcomers. | Strong franchise identity and innovation make Halo stand out, but inconsistent execution affects long-term player trust. |
| **Valorant** | - Tactical, team-based gameplay that emphasizes strategy.<br>- Unique agent abilities add variety.<br>- Optimized for competitive play with low hardware demands. | - Steep learning curve for casual players.<br>- Toxicity in competitive community.<br>- Limited appeal outside esports scene. | Appeals strongly to competitive players and esports fans, but casual gamers may feel excluded or overwhelmed. |


 Pseudocode and Flowcharts: Create pseudocode and flowcharts to represent the key aspects of your
project. This will help you visualise and plan your project’s functionality.

**PSEUDOCODE**

BEGIN GAME

INITIALIZE player stats (health, ammo, score)

LOAD level environment

DISPLAY HUD (health, ammo, score)

WHILE game is running:

    READ user input
    
        IF W/A/S/D pressed → MOVE player
        
        IF mouse moved → ROTATE camera/aim
        
        IF Left Mouse Click → FIRE weapon
        
            CHECK collision with enemy
            
            IF hit → REDUCE enemy health
            
            IF enemy health <= 0 → REMOVE enemy, INCREASE score
       
        IF Right Mouse Click → AIM down sights
        
        IF Spacebar pressed → JUMP
        
        IF Shift pressed → SPRINT
        
        IF Ctrl pressed → CROUCH
        
        IF R pressed → RELOAD weapon
        
        IF E pressed → INTERACT with object

    UPDATE HUD (ammo, health, score)
    
    CHECK player health
    
        IF health <= 0 → DISPLAY "Game Over", END game
    
    CHECK objectives
    
        IF objective complete → DISPLAY "Mission Complete", LOAD next level

END GAME


**FLOWCHART** (look in editing mode to see the flowchart correctly, I was having some embedding issues I couldn't solve)

          ┌───────────────┐
          │   Start Game  │
          └───────┬───────┘
                  │
        ┌─────────▼─────────┐
        │ Initialize Player │
        │ Health, Ammo, HUD │
        └─────────┬─────────┘
                  │
        ┌─────────▼─────────┐
        │   Read Input       │
        └─────────┬─────────┘
                  │
   ┌──────────────┼─────────────────────────┐
   │              │                         │
┌──▼───┐     ┌────▼────┐              ┌─────▼─────┐
│Move  │     │Fire Gun │              │Interact   │
└──┬───┘     └────┬────┘              └─────┬─────┘
   │              │                         │
   │        ┌─────▼─────┐                   │
   │        │Collision? │                   │
   │        └─────┬─────┘                   │
   │              │                         │
   │        ┌─────▼─────┐                   │
   │        │Enemy Hit? │                   │
   │        └─────┬─────┘                   │
   │              │                         │
   │        ┌─────▼─────┐                   │
   │        │Update HUD │                   │
   │        └─────┬─────┘                   │
   │              │                         │
   └──────────────┼─────────────────────────┘
                  │
        ┌─────────▼─────────┐
        │ Check Player HP   │
        └───────┬───────────┘
                │
        ┌───────▼───────────┐
        │ HP <= 0 ?         │
        └───────┬───────────┘
                │Yes
        ┌───────▼───────────┐
        │ Display Game Over │
        └───────────────────┘


**GANTT CHART**
[Gantt chart link](https://docs.google.com/spreadsheets/d/1ODpN5XkP_Fm8j_PlDokTxcTzkj1v0Nv66YLY0LCduQI/edit?usp=sharing)
