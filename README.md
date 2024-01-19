## **Projects**
---
[__HOME__](https://kronedev22.github.io)

[__About Me__](https://kronedev22.github.io/AboutMe/)

---

## **Completed works**

---

## **Bees 'n' Trees**
[Unity + Godot] (Solo) 

{% include youtube.html id="vw6tjmAxFS8" %}

[__View Game - Itch.io__](https://kronedev.itch.io/beesntrees-slingy-bee)

#### **About the game**
- Made with Unity as my first game, and recently remade in Godot
- Controls with clicking on the bee and sliding your finger in the direction to move, then releasing to launch
- Points are gained through each unique gap passed through
- Game play ends when the player touches the spikey vines at the top or bottom of the screen

#### **Initial goal**
This initial goal of this game was just to get more experience in Unity, and seeing as though the idea was simple, I figured the scope small enough, to carry it all the way through.

#### **What was learnt**
- Documentation and scheduling is always helpful
- OnMouseDown() and OnMouseUp() also work when ported to Android devices
- The KISS principle can apply to pixel art

--- 

## **Maid Mayhem**
[Unity] (Group - Role = Project lead/ Programmer) 

{% include youtube.html id="57M4mohm2Vs" %}

[__Play Game__](https://play.unity.com/mg/other/webgl-builds-360558)


#### **About the game**
- Made in Unity, as part of assessment
- Fast paced, high score, time trial
- Two different types of minigames (messes), with 3 difficulty variants each
- Player has access to one tool per mess type (Broom = piles, mop = spills)
- Mop is required to be wet at a bucket to then be used
- Completing a minigame awards points
- Fulfilling a condition when completing a minigame also grants extra time
- Messes spawn in gradually, with custom waves spawning on a set timer
- Player performance receives a rank on the end screen

**My contributions (programming):**
- Player movement
- Minigame functionality + condition
- Assisted with mess/ wave spawning
- Level timer + score
- End screen + player ranking
- UI + UI animations
- Ending the game early (by walking out either door)

#### **Initial goal**
The scope of the game started off larger than what was delivered, this seems quite frequent. 
One of the first ideas was quite similar, but instead of having a single room per level, the player would reach a score threshold which would unlock access to the next room.
Each room having a different layout and being a little more challenging. Overall this game went through a number of iterations to reach an achieveable idea within the trimester.

#### **What was learnt**
- Project management++
- More knowledge on scrum and agile methodology
- More experience in a team scenario

---

## **Cardmancer**
[Unity] (Group - Role = Project lead/ Programmer) 

{% include youtube.html id="QpaLrlTDF4w" %}

[__View Game - Itch.io__](https://kronedev.itch.io/cardmancer)

#### **About the game**
- Made with Unity as a capstone project at Uni, and was developed over 12 weeks (as there were team changes over the break between trimesters)
- Fast paced, strategy, roguelike
- Customise your deck with the cards of your choice
- Enter an arena, small or large
- Enemies get stronger as the waves get higher
- Player has a choice of upgrades after every 5 waves (upgrades are applied to the card slot, instead of the cards themself)
- Fight 5 different types of enemies with your customised deck, by throwing the cards or setting them on the ground as a trap
- Each card has a number of other cards it can interact with, which can be used to achieve more powerful results
- Upon the game ending, view stats to see how well you did

#### **Initial goal**
This game was developed with the main thought of making a card game, that doesn't feel like other card games (faster pacing, while keeping the strategy aspects).

#### **What was learnt**
- What it's like working with another programmer on code that overlaps
- When to listen to feedback/ suggestions, and ignore those that don't aline with the games vision
- More experience with GitHub branches
- When to use third party resources to speed up development (Mixamo was used for animation, third party sounds were used)
- How nice it is to have daily communication
- VFX Graph
- Shader Graph

---

## **Works in progress**

---

## **Project TPS-AimingSystem**
[Unity] (Solo) (On hold)

{% include youtube.html id="oxscby7NH4c" %}

#### **About the game**
- Basic WASD movement
- Resident Evil 4 styled aiming system
- Each gun animated programmatically (aim, recoil, reload, idle)
- Player held weapons displayed on their back
- Projectile and beam based weaponry
- Guns created with scriptable objects (very easy expansion)
- Generic health script used for taking damage
- "Manouvems" - A system similar to that of stratagems from HELLDIVERS
- Each "manouvem" is a scriptable object
- The player can hold CTRL, and press 1 - 4 to quickly input a set code (such as CTRL+1, to input, WWA), to allow players quicker access to either frequently used manouvems, or their favourites
- A console allowing the player to equip different guns during runtime
- The same console, allowing players to set their manouvem quick access codes

#### **Initial goal**
This project started off as simply making an aiming system similar to that in RE4. 
Once that was achieved, it just kept going as I kept learning, starting with the procedural aiming of the gun, and then recoil, reloading, and so on.

#### **What was learnt**
- Experience with the inbuilt quaternion functions (such as Quarternion.Rotate())
- Scriptable objects
- What abstract, virtual, and protected meant, and their uses
- Coroutines
- Rigidbody.SweepTestAll() and Rigidbody.SphereCastAll()

#### **Plans that could have been**
- Simple player model using IK on the hands to hold the guns (allowing the guns to remain programmatically animated)
- Simple enemies (in both AI and shape/ detail)
- A console for the player to choose their own equipment (Implemented)

**Gameplay loop:** Player is in a small "hub" type area with access to the console and a firing range.
When ready to set out, the player may interact with an object which would then generate a level using an asset called "Advanced Dungeon Generator".
Once generated, the door would open and the player would leave to fulfill an objective, and when the objective is complete, return to the hub and close the doors, unloading the generated area.
The player could then change equipment if wanted, and set out again.
As this could get repetitive, rewarding the player with new weapons/ manouvems would be the incentive.

---

## **Project ProcWorld**
[Unreal Engine 5] (Solo) (Current)

{% include youtube.html id="uCMgitspV-U" %}

#### **About the game**
- Basic WASD movement
- Interaction system (currently to pick up items)
- 5 hotbar slots (selectable via scrolling or 1-5)
- 20 inventory slots (revealed with TAB)
- Randomly generated modular melee weapons and spells
- Placeholder potion and material items (currently unusable)
- All weapons/ items animated through blueprints
- Simple damage system, with armour and armour penetration

#### **Initial goal**
The goal of this project was to make a procedural world, with modular weapons. 
After researching how to make a procedural world, I made the modular weapons. I really liked the outcome of the modular weapons, so made them usable. 
At this point, I started wanting to take it further, and possibly all the way to a finished game, so started planning for that by making documentation to flesh out the idea.

#### **What was learnt**
- LOTS about blueprints
- Blueprint structs
- Blueprint interfaces
- Blueprint master/ child classes
- Widgets
- More to come

#### **Potential plans**
- Modular weapons with unique effects
- Enemies with some form of AI
- Character customisation
- VFX (using the niagara system)
- A station to upgrade weapons/ spells/ and the players armour
- A randomly generated quest system
- A merchant to sell items to, and buy potions from
- Procedural animations for the player character, and enemies
- Monster hunter like enemies that roam about (probably too ambitious)
- Online co-op

**Gameplay loop:** The player is an adventurer, and each day would go to the adventurers guild to choose a random quest (Kill X, Gather Y, etc.).
The player could then purchase goods before heading off.
While out completing the quest, the player could explore some to find upgrade materials or other challenges.
Once the quest is complete, the player would return to hand in the quest.
Then upgrade, if available, and finally turning in for the night.
(Lots of room for potential additions, such as staying out for the night and dealing with a different challenge, or even just hanging out by a campfire).
