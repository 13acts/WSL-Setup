# WSL Setup for Windows
## Step by step guide to set up WSL and VS Code for the first time on Windows
----------

## Install necessary apps
1. Install VSCode
2. Download Ubuntu from Microsoft Store (choose the one with only Ubuntu, without version numbers)
3. Install Ubuntu, restart PC, open WSL and set up username and password
4. On VSCode, install WSL extension (use *v.75.3* to have Open Folder option in the Search bar)
5. >Open Folder in WSL
----------

## Additional steps to install Python and flask
### To transit from CS50 Codespace to coding locally for the Final Project
6. `sudo apt-get update`
7. `sudo apt-get install python3`
8. `sudo apt-get install python3-pip`
9. `sudo apt-get install python3-flask`
10. `pip3 install flask_session`
11. `pip3 install cs50`
12. `pip3 install requests`
13. `sudo apt-get install sqlite3`
14. `.mode table`
----------

## Run flask in debug mode
15. `export FLASK_DEBUG=1 && flask run`
----------
