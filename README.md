# Tangerine-Tycoon-stockmarket-bot
A simple bot for automating playing on stockmarket in The Tangerine Tycoon flash game

// A bot for easier trading in the Tangerine Tycoon stock market
// minigame.

// The bot is only tested to work properly 
//   for the Tangerine Tycoon v1.26 
//   in Mozilla Firefox (not compatible with Chrome) 
//   with page scale set to 100% (not compatible with other scales)
//   with flash player quality set to "high" (not compatible with other quality settings)
//   under Windows 7 (wherever SCAR Divi 3.40 is working) 

// Instruction:
// 1) Download and install SCAR Divi 3.40 
//    (download: http://www.scar-divi.com/download.php?file=scar-3.40.00-setup.exe)
// 2) Open this script in SCAR
// 3) Open the Tangerine Tycoon in Firefox browser (Chrome will not work)
//    (kongregate: http://www.kongregate.com/games/GazThomas/tangerine-tycoon)
// 3.1) Page scale should be 100%, set it properly by ctrl + mouse wheel!
// 3.2) You should have at least 50 tangerines! Earn them right now if you don't!
// 4) Go to The Tangerine Exchange screen (press right arrow on the main screen)
// 4.1) Click "Purchase Volume: 50%" in the lower right corner of the game screen
// 5) Target the flash game subscreen with SCAR, dragging the "Crosshair" icon
//    onto the game flash screen in the browser window
// 5.1) Whenever you move the browser window, you should re-target the game screen
//      with the "Crosshare" tool in SCAR
// 6) Launch the bot ("Play" button in SCAR). 
// 6.1) WARNING! The bot will stop working if the "Price" column is blocked by
//      achievement panels. Watch them from time to time and close them manually!
// 6.2) You can play the game as usual, but bot will act only when The Tangerine
//      Exchange screen is opened.
// 6.3) You can work with other programs as well, the bot will act whenever
//      the game screen is visible. 
// 7) Whenever you feel to stop the bot playing, press "Stop" in SCAR.

// Troubleshooting:
// - If the bot stopped working, try to re-target the game window, dragging
//   the "Crosshair" tool from SCAR toolpanel to the flash screen of the game.
// - Please, ensure the page scale is set to 100%. The bot will not recognise
//   the fonts of the game otherwise.
// - Bot can work properly only when the "Price" and the "Buy/Sell" columns of the
//   Exchange screen are visible
// - If bot strangely "jerks" the mouse cursor way too often, ensure
//   that the "Purchase Volume" on the Exchange screen is set to 50% (NOT 100%)
