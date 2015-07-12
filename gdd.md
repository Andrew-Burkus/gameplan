# AntiGravity
My Game Thing

##Objective
Infinite side scroller.
You cannot control the character directly, you may only alter the environment's gravity.It's hard to dodge stuff because of this. There are power-ups which can be bought with the coins a player earns in game. At some point there may be in-game purchases for players who are willing to waste their money

##Mechanics
Swiping is key. Swipe up and down to alter state of gravity. Power-ups are a thing now. Players can spend points they earn in-game on power-ups that will help them live longer and gain more points in future sessions.

##Level Design
Simple, and ranging from nearly impossible to quite easy. Each level is a box/coin configuration

##Technical
1. Controls
  * Swipes
  * Up or Down only
  * Tapping power-up icons activates corresponding power-up
2. Scenes
  * Infinite side scroll with random scenes
  * Game over screen shows high score and previous score
3. Class and CCBS
  * Hero is just a standard CCSprite.
  * Levels are Layers of equal size
  * Gameplay is a special layer with all game logic.
  * tutorials are layers with special animations and text
  * Store is a layer.

##MVP Milestones
* 12-18
  * Add a distance counter thing
    * distance labels
    * User defaults assignment
  * Higher-end Tutorial
    * explain Power-ups
    * explain swiping on a goddamn screen
    * explain avoiding obstacles
* 19-25
  * Implement Global Leaderboard
* 26-1
  * Ship
