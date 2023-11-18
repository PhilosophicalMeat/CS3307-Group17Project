
# How to run the game on a pi

* Install the following dependencies:
   - SDL dev `sudo apt-get install libsdl2-dev`
   - SDL image dev `sudo apt-get install libsdl2-image-dev`
   - SDL mixer dev `sudo apt-get install libsdl2-mixer-dev`

* After installing depenendencies run `make` from the root folder.
* To start game run `./game` 


# Notes for TA about acceptace tests
Some of the acceptance are not fully valid since some parts of the game are still in development (parts that are not included in the selected stories for this stage). I have emailed the prof and he said to
make note of it in the README to not lose marks on those acceptance tests:
### Game UI - Start screen Acceptance tests
* "The user can view the high score board by clicking the high score board option"
    * currently high score screen is not implemented so score button will bring user to blank screen
    
 ### Game UI - Health bar, Score counter, Wave tracker Acceptance tests
 * "player score increases when an enemy is killed"
    * score system not implemented yet so this will not show
* "wave counter should increment when a wave finishes"
    * wave system not implemented yet so this will not show
 
 ### Game Mechanic - Player/sprite that can move and shoot Acceptance tests
 * when enemy takes damage its not visible to user until the damage enough to kill enemy

 ### Closed stories:
 - Game UI - Start Screen
 - Game Mechanic - Player/sprite that can move and shoot
 - Game Mechanic - AI enemies and asteroids
 - Game Audio - Sound Effects
 - Game Audio - Music (Opt Feat)
