[birdy]: imgs/birdy.png "birdy"
[wireframe]: imgs/wireframe.png "wireframe"
# FlexBox Birdy
[!alt text][birdy]
  FlexBox Birdy is a CSS game that draws inspiration from FlexBox Froggy made Thomas Park.

  In FlexBox Birdy, birds are lost from their nests and the player needs to help them get back home using their flexbox skills.

# Functionality & MVP

In FlexBox Birdy, users will be able to:

* use css to move birds on the screen
* have different levels
* descriptions and hints for each level
* levels save using local storage

* production read me

# Wireframes

Game will consist of a single page with a field on the left to input css/flexbox properties with the side of the page displaying the "game". Instructions for each level will be displayed in the top left.
At the bottom there will be nav links to my Github and LinkedIn.

[!alt text][wireframe]

# Technologies and Architecture

* Animate.css for animations in the game
* Vanilla JS & JQuery for game logic and structure
* Webpack to bundle all scripts

The following design will be used for FlexBox Birdy:

* game.js - will take care of the game logic and load levels
* levels.js - holds all the information of each game levels & information on how to complete the levels

# Implementation Timeline

**Day 1**

* Create game.js and first two levels in level.js
* Get basic jQuery working to change the properties of the birds and make them change position.

**Day 2**

* Get localStorage working for remembering levels
* Style website into wireframe and make the correct level set up work for both levels.
* Begin working on basic game logic in game.js to take in input and check for win conditions

**Day 3**

* Continue on basic game logic in game.js
* Style and begin implementing animate.css on parts of the game

**Day 4**

* Finish win conditions in game.js & begin to create more levels in level.js
* Style to make the game feel robust

# Bonus

* More than 5 levels
* Other css tricks other than flexbox