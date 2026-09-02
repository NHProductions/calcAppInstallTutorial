# calcAppInstallTutorial
Simple tutorial for installing assembly games onto the TI-84 CE:

Things needed:
- TI-84 CE or TI-84 CE Python calculator.
- Its charging cable
- A windows computer

# Installing everything you need:
1. Get your calculator, its charging cable, and a computer.
2. On the computer, install [TI Connect CE](https://education.ti.com/en/software/details/en/CA9C74CAD02440A69FDC7189D7E1B6C2/swticonnectcesoftware).
4. Connect your calculator your computer using the charging cable.
5. Open TI-Connect CE.
6. On your calculator, press "2nd", then "catalog".
7. If "asm(" is one of the first ~15 options, go to step 9. If not, go to Step 8.
8. Download then transfer onto your calculator [Artifice Jailbreak](https://yvantt.github.io/arTIfiCE/). Transfer files to the calculator by dragging & dropping, then clicking confirm.
9. Download & Install the rest of the files you need:
    - [Cesium Installer](https://www.ticalc.org/archives/files/fileinfo/465/46574.html) (Or some other Ti-84 CE Shell); this will actually allow you to run the things
    - [CLibs](https://github.com/CE-Programming/libraries/releases/tag/v15.0) - This contains functions and other things vital for making TI-84 CE applications. Make sure you download clibs.8xg.
10. If you have "asm(", press "2nd", then "catalog", then select "asm(". Then, select the cesium installer by going to prgm, then selecting cesium. The current line should be "asm(prgmCESIUM". Press enter. It will then install cesium onto your calculator, and then ask if you want to delete the installer.
11. If you do not have "asm(", go to prgm, and run Artifice. It will give you a list of programs to run using Artifice. Select Cesium. Cesium will then install and ask if you want to delete the installer.

# Installing & Running games and apps:
1. Go to the app's website or webpage.
2. Find a .8xp file from the app. It usually is in the "bin" folder, but may vary depending on the app.
3. Download the .8xp file, and add it to your calculator. If the app has anything else needed (such as images or other assets), follow the developer's instructions on how to install them.
4. Go to apps, and select Cesium. In cesium, you will see all the games/apps you have downloaded. Select a game/app you want to play, and press enter.

If you are here for games, below are my apps that are made for the TI84 CE.

Games:
[Oregon Trail](https://github.com/NHProductions/OregonTrail) - Semi accurate recreation of the Oregon Trail  
[Minesweeper](https://github.com/NHProductions/TI-84-CE-Programs/tree/main/SWEP) - Minesweeper for the TI84 CE.  
[Blackjack](https://github.com/NHProductions/TI-84-CE-Programs/tree/main/BLCKJK) - Blackjack for the TI84 CE.  
[Tetris](https://github.com/NHProductions/TI-84-CE-Programs/tree/main/TETRIS) - Semi-accurate recreation of tetris (semi-accurate as in totally different graphics but essentially same gameplay)  
[Pong](https://github.com/NHProductions/TI-84-CE-Programs/tree/main/PONG) - This one is one of the first games I created for the TI84 CE, so it's quite buggy, but it works okay enough.  
  
Apps:  
[Crimson CAS](https://github.com/NHProductions/CrimsonCAS) - Computer Algebra System (Quite buggy, but it works alright for things like systems & algebraic equations)  
[Blusky](https://github.com/NHProductions/Blusky) - Not really recommended to use this one; Cesium already does basically all the things this does. This is essentially a file explorerer for the TI84 CE; however, it's quite buggy lol.  
[Atlas](https://github.com/NHProductions/Atlas) - This is a video player for the TI84 CE. Setup is quite complicated, but if you have experience in python, then you're probably able to set this up and convert videos for the TI84 CE.  
