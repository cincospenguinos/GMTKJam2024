# README.md

Godot game for GMTK Game Jam 2024

* OBJECTS IN THE WORLD
  * Mirrors to bounce off lasers
  * Splitters as well
  * Lasers! They hit things on a grid and give resources per unit time
    * Lasers could be upgradable!
      * Lasers can be configured with their own inventory puzzle
      * Putting things in lasers increases various yields
    * Lasers can be different colors! Different colored lasers can't cross each other
    * Lasers can be split into multiple streams and hit multiple objects
    * Longer lasers yield greater resources
    * Do lasers need power? How are they powered?
    * Do we want to require transport of resources?
      * Each map has an extraction point, and you place items to get resources back to the extraction point
      * Lasers extract using anti-gravity, and the path they take to the resource space is the path the resources go back
      * Are lasers the extraction point, or do they simply accumulate resources?
  * Beacon that increases various attributes by radius
  * Walls/obstructions
  * Terrains that can/cannot be built upon
  * Scaffold/items to terraform (get rid of water, expand water, rough terrain, etc.)
  * The laser is the harvester; gathering the resources is something that needs to be done by the character or figured out by moving things to the extraction point
* SHOP/Macro loop
  * Given some set of resources provides objects that you can use in the world
* Resources! We have them!
  * Wood
  * Stone
  * Autoclickers
  * Meat/Cheeseburgers
  * Ore(s)
* Are you a character and you're moving around?
  * If so, you have a little grid to interact with for mining and extracting resources, but moving around as a person is slow because you're tiny compared to the mining operation
* You can collapse the map into a cookie or button that can be clicked
  * Clicking the button gives you the resources contained inside
  * You can assign autoclickers to a button to give you that resource accumulation at regular intervals
  * You can take the collapsed map and place it as an item on the current map to become a resource available to be mined
* Players start in the map
* When you start a map, you must get it to a stable state. Once you've done that, you hit "save" and it turns it into a button to be clicked
  * You can click the button to get the resources from it
  * You can then click to go to a new map and extract new things with new lasers+items built in the macro view
  * You can extract each map into a new button to click
* Players can come back to the macro view to select things to build
* Resources are tiered
  * Wood + Stone, once invested in, yield metal harvesting
  * Metal harvesting can lead to metal perfecting
  * Atomic age comes after metal harvesting offering uranium, plutonium, the abstract concept of love
  * You win the game when you build a dyson sphere out of enough uranium, plutonium, and love
* When you enter a map, all tiers are on the map, but locked tiers are not available to the player
  * When the player sees locked tier resources on the map, they can't be built on/interacted with (they're just mountains or marshes or swamps or islands) until the tier is unlocked
* How do we do the button into map thing?

## PHASE 1 - MVP

## PHASE 2

## PHASE 3
