# meteors-game
I wanted to create a game in the space idea, here is the list i did to describe it :

Develop a simple game where asteroids appear randomly across the screen. The player controls a spaceship and must avoid colliding with the asteroids while collecting coins that also appear.

Only one coin should be present on the screen at any given time. Once a coin is collected, another one will respawn, indicated by a directional arrow pointing to its location.
The asteroids start from random points outside the window and move in a straight line at a customizable speed determined by a variable.
To collect a coin, the player's spaceship needs to pass over it. Collected coins contribute 100 to the player's score. Additionally, every centi-second passed without dying increases the score by 1.
The collected coins persist and can be used in a visual shop interface accessible from the main menu. The shop takes the entire screen, with a black background and a 'Main Menu' button at the bottom right. Upgrades are displayed in rectangles (outlined in white) with rounded corners. Clicking the 'Buy' button opens a window displaying the current and upgraded stats (e.g., speed: 1 >>> 1.1). Below the upgrade details, there are 'Buy' and 'Cancel' buttons. If an upgrade is unavailable due to insufficient coins or reaching the purchase limit, the 'Buy' button appears red or doesn't appear at all.
All upgrades are initially available for purchase if enough coins are collected. However, upgrades have a limit of 10 purchases each. Upgrades include increasing the speed of the spaceship, decreasing the speed of the meteors, increasing spaceship health, and adding a space shooter with a 3-second cooldown. The shooter initially destroys one meteor per shot. Players can upgrade to increase the number of meteors destroyed per shot, but this upgrade is also limited to 10 purchases.
The spaceship's health is represented by a simple yellow life bar, divided equally by a black line if more than one life is available, providing a visual indicator of the spaceship's health level.
Upon reaching zero health, the game transitions to a black screen with red text displaying 'Game Over.' Players are presented with options to return to the main menu or immediately start a new game.
