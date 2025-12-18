# Murder Mystery 200 Players

**Murder Mystery 2** is a popular multiplayer social deduction game on the **Roblox** platform, created by **Nikilis**.

## 🔥 HypeHype version

One of the most exciting features of the game is **automatic role scaling** based on the number of players in a match.

- For **every 6 players**, the game automatically adds:
  - **1 Murderer**
  - **1 Sheriff**

This dynamic scaling keeps matches intense and balanced, making gameplay more chaotic and fun as the player count increases.

## 🎮 Gameplay Overview

In each round, players are randomly assigned one of three roles:
- **Innocent** – Try to survive, collect clues, and identify the murderer.
- **Sheriff** – The only player with a gun, responsible for stopping the murderer.
- **Murderer** – Eliminate all players without being caught.

## 🕵️ Objective

Each role has a different goal:
- Innocents must stay alive and help the Sheriff.
- The Sheriff must protect Innocents and defeat the Murderer.
- The Murderer must eliminate everyone while remaining hidden.

## ⭐ Key Features

- Fast-paced rounds with suspenseful gameplay  
- Emphasis on deception, observation, and strategy   



[![Watch the video](https://img.youtube.com/vi/VIDEO_ID/0.jpg)](https://www.youtube.com/watch?v=bZ5OBDHFqj0)






## Murder rules

**Responsible for the game rules.**

- It validates and processes player kills — for example, when Player 1 kills Player 3, it decides who should receive the death signal.
- If needed, it also handles ending the game


  

## GameCore

**Responsible for starting and ending the game.**

- Essentially, it acts as a timer and also creates virtual lobbies.





## Admin Controller

**A simple communication tool with the server.**

- It sends admin commands to Neo, such as starting or ending the game.





## GameСlientsListene

**This is a client-side script.**

- It listens for commands from MurderRules
- for example, when a player is killed, when the game ends, or when the player picks up a gun, etc.





## GameEventsLocal

**Used to notify the server when something happens locally**

- for example, when a player gets hit or picks up a gun.






## GameUI Controller

**Responsible for the UI logic handling**





## AnimPlayer

**Responsible for the handling of the player animations logic**





## AdvancedWeaponController

Advanced reworked Team shooter logic
