## **Projects**
---
[__HOME__](https://kronedev22.github.io)

[__About Me__](https://kronedev22.github.io/AboutMe/)

---

## **Bees 'n' Trees**
(Solo)

{% include youtube.html id="g-sgw9bPV4A" %}

#### **About the game**
- Controls with clicking on the bee and sliding your finger in the direction to move, then releasing to launch.
- Points are gained through each unique gap passed through.
- Game play ends when the player touches the spikey vines at the top or bottom of the screen.

#### **Initial goal**
This initial goal of this game was just to get more experience in Unity, and seeing as though the idea was simple, I figured the scope small enough, to carry it all the way through.

#### **What was learnt**
- Documentation and scheduling is always helpful.
- OnMouseDown() and OnMouseUp() also work when ported to Android devices.
- The KISS principle can apply to pixel art.

--- 

## **Maid Mayhem**
(Group - Role = Project lead/ Programmer)

#### **About the game**
- Fast paced, high score, time trial.
- Two different types of minigames (messes), with 3 difficulty variants each.
- Player has access to one tool per mess type (Broom = piles, mop = spills)
- Mop is required to be wet at a bucket to then be used.
- Completing a minigame awards points.
- Fulfilling a condition when completing a minigame also grants extra time.
- Messes spawn in gradually, with custom waves spawning on a set timer.
- Player performance receives a rank on the end screen.

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
- Project management+
- More knowledge on scrum and agile methodology
- More experience in a team scenario

---

## **Project TPSAimingSystem**

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

#### **Initial goal**
This project started off as simply making an aiming system similar to that in RE4. 
Once that was achieved, it just kept going as I kept learning, starting with the procedural aiming of the gun, and then recoil, reloading, and so on.

#### **What was learnt**
- Experience with the inbuilt quaternion functions (such as Quarternion.Rotate())
- Scriptable objects
- What abstract, virtual, and protected meant, and their uses.
- Coroutines
- Rigidbody.SweepTestAll() and Rigidbody.SphereCastAll()

#### **Future plans**
- Simple player model using IK on the hands to hold the guns (allowing the guns to remain programmatically animated).
- Simple enemies (in both AI and shape/ detail)
- A console for the player to choose their own equipment

Gameplay loop: Player is in a small "hub" type area with access to the console and a firing range.
When ready to set out, the player may interact with an object which would then generate a level using an asset called "Advanced Dungeon Generator".
Once generated, the door would open and the player would leave to fulfill an objective, and when the objective is complete, return to the hub and close the doors, unloading the generated area.
The player could then change equipment if wanted, and set out again.
As this could get repetitive, rewarding the player with new weapons/ manouvems would be the incentive.
