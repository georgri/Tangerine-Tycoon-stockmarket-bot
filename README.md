# Tangerine-Tycoon-stockmarket-bot
A simple bot for automated trading in the Tangerine Tycoon stock market minigame.


**TO STOP THE BOT IN CASE OF EMERGENCY: Ctrl+Alt+S** 


General description
===============================
The bot buys commodity when it goes below 30 tangerines for 50%
of the available money and then sells it when it goes above 80. 
The bot behaviour is not smart nor optimal. Playing manually will benefit you
more quickly. The bot is useful when you are away for several hours and your
computer is always on.

Requirements
===============================
The bot is only tested to work properly 
- for The Tangerine Tycoon v1.26 
- in Mozilla Firefox (not compatible with Chrome) 
- with page scale set to 100% (not compatible with other scales)
- with flash player quality set to "high" (not compatible with other quality settings)
- under Windows 7 (wherever SCAR Divi 3.40 is working) 

Instruction
===============================
1. Download and install SCAR Divi 3.40 
   (download: http://www.scar-divi.com/download.php?file=scar-3.40.00-setup.exe)
2. Open this script in SCAR
3. Open the Tangerine Tycoon in Firefox browser (Chrome will not work) (kongregate: http://www.kongregate.com/games/GazThomas/tangerine-tycoon)
  - Page scale should be 100%, set it properly by ctrl + mouse wheel!
  - You should have at least 50 tangerines! Earn them right now if you don't!
4. Go to The Tangerine Exchange screen (press right arrow on the main screen)
  - Click "Purchase Volume: 50%" in the lower right corner of the game screen
5. Target the flash game subscreen with SCAR, dragging the "Crosshair" icon onto the game flash screen in the browser window
  - WARNING! Whenever you move the browser window OR scroll the page, you should re-target the game screen with the "Crosshare" tool in SCAR
  - The game has now got an "autofocus" feature that tries to automatically target the game screen and resize the page to 100% scale.
6. Launch the bot ("Play" button in SCAR or press Ctrl+Alt+R). 
  - WARNING! The bot will stop working if the "Price" column is blocked by achievement panels. Watch them from time to time and close them manually!
  - You can play the game as usual, but bot will act only when The Tangerine Exchange screen is opened.
  - You can use another browser window for browsing while bot is playing. 
  - You can work with other programs as well, even blocking the game screen with other window. The bot will shortly activate the game window from time to time to press an appropriate button in the game. It will appear as if the browser window will "flicker" for a moment.
7. Whenever you feel to stop the bot playing, press "Stop" in SCAR. (Global shortcut: Ctrl+Alt+S)

Troubleshooting
===============================
- If the bot stopped working, try to re-target the game window, dragging the "Crosshair" tool from SCAR toolpanel to the flash screen of the game.
- Please, ensure the page scale is set to 100%. The bot will not recognise the fonts of the game otherwise.
- Bot can work properly only when the "Price" and the "Buy/Sell" columns of the Exchange screen are visible
- If bot strangely "jerks" the mouse cursor way too often, ensure that the "Purchase Volume" on the Exchange screen is set to 50% (NOT 100%)  


Future improvements
===============================
- TODO: Tutorial with pictures
- TODO: Add mode to quickly unlock 100 universes. 
  - Every 5 minutes go to main screen and try to buy the last not bought item
  - Stop when successfully bought The Tangerine God 
  - => go to achievement screen and press Breach the Universe
  - => skip the cutscene, press 1000 times on a tangerine, buy a couple of structures, go to The Tangerine Exchange screen
- TODO: If buying 5th resource, spend all the money
- TODO: Auto switch to 50% purchase Volume at the start
- TODO: Go to the Exchange screen from any screen at the start
- TODO: think of advanced strategies of spending 100% resources on lowest resource
- NOTE: Using Hinting does not help much in trading! :(
  - The only usefull feature: '+' goes to '-' only when it's >= 80
  - Anyway, it's kinda BS, not gonna do anything about it

