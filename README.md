# skiGame
- Set Up
    - fork the skiGame directory (https://github.com/nlevin11/skiGame)
    - pull and open the directory
- About
    - the index.html is the html file, which links to main.js and the Three.js library
    - main.js links to GameManager, which links to Player and Obstacle
    - Player manages the player, obstacle the obstacles, and GameManager everything else (main does nothing but init a new gameManager)
    - the assets folder contains 3D models (.glb) of a skier, rock, and tree, but these models have not yet been implemented
    - animate() in GameManager is the main function that controls the game, init() in GameManager starts the game
    - Three.js does not require downloading anything
- How to Run
    - 2 options:
        - firebase serve- open public directory in this directory on terminal, type firebase serve
        - use the Live Server extension on vs code if firebase serve does not work