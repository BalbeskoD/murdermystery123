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
