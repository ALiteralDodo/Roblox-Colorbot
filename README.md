# EDUCATIONAL PURPOSES

This project is currently being maintained slightly, but is meant primarily to be used as a way to learn.
It will not be maintained forever.

# COPYRIGHT:
(Note: Written with the help of ChatGPT because I'm lazy)
Copyright 2023

Permission is hereby granted, free of charge, to any person obtaining a copy of this Python software and associated documentation files (the software), to deal in the software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, and to permit persons to whom the program is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the program.

Any fork, modification, distribution, or use of the Software that does not adhere to the following conditions is prohibited:

1. Redistributions of this Python program must include proper attribution to Seconb and a link to the original repository.
2. Any modification or derivative work based on the Software must be clearly marked and identified as such.
3. Prior written permission must be obtained from the original author(s) for any commercial use of the Software.
4. The derivative work is not used commercially or otherwise involved financially
5. Changes have been made to the code as improvements must be supplied through GitHub. Ergo, if a user wishes to improve it, the changes cannot be made in another repository or download page.

THE SOFTWARE IS PROVIDED "AS IS," WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

# USAGE GUIDE (From the source)

- Windows 10/11 Only! May have issues on some stretched or otherwise unusual resolutions (i.e 1152x852 or 1366x768). 1080p, 1440p, or 4k is recommended. Mouse Acceleration should be turned off for best results.

- Download the Source code, then extract it to a folder. Run installer.bat as admin. YOU WILL PROBABLY NEED TO TURN OFF WINDOWS DEFENDER, ITS A FALSE POSITIVE NOT A VIRUS YOU CAN READ THE SOURCE CODE ITS OPEN. After that you can run the .py

- Enable "Enemy Color Outlines" in Arsenal settings

- Drag each R G B slide in the settings all the way to the right, then back to the left to fix a bug in Arsenal.

- Change them to the color you choose in the config.ini. Your options are Green, Yellow, Pink/Magenta/Purple and Blue. Capitalization is unimportant as long as you spell the color correctly.

- Note: When using pink/magenta/purple, make sure that you change the crosshair color as the default is the same color as the enemies. Otherwise, the aimbot's not gonna work.

- Once you set the config with the color and did the color in Arsenal settings, open aimsource.py.

# TROUBLESHOOTING

- Do not contact me on Discord with your troubles. Only use the "Issues" tab in this GitHub. I will not take any longer than maybe a few minutes to attempt to help you, and that is final.

- If the installer fails at installer.bat, download Python: https://www.python.org/ftp/python/3.11.7/python-3.11.7-amd64.exe . After opening that, check "Add Python.exe to PATH" before installing **REALLY IMPORTANT**. Then, open cmd (command prompt) as admin and run:
    - pip install Pillow mss configparser opencv-python numpy colorama pywin32

- Aim shaky? Lower your speed
  
- Crashing? Screen record your screen and include the program's GUI. Send the error to the "Issues" tab in a new issue on this GitHub page.

- Not aiming at all? Make sure you set the color correctly. You must FULLY slide the R G B bar under "Enemy Color Outlines". Also make sure you did the part where you slide each color bar fully to the right then fully to the left before setting the correct color (fixes an Arsenal bug). If that doesn't work, try exiting "True" Fullscreen or attempting to use WindowedFullscreen (both of these are not included with default Roblox). If this doesn't work, try it without Bloxstrap or any other optimized Roblox version. If you are using the UWP, try using the web version. Please also ensure that Valorant, FACEIT, or any EAC-protected games are closed. (These anti-cheats either block or will ban you for using this script even though you are not actively using it in their game)
