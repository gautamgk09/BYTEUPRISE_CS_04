## HOW IT WORKS

This tool utilizes a packet capture library to identify STUN packets from any peer-to-peer connection, enabling the determination of connected peers and ping values. Designed for Steam API-based games, it leverages the Jingle library to handle STUN functions within the Steam API.

It operates discreetly and is not detected as a hack, as it does not directly interact with any game.

## APPLICATION SUPPORTS BOTH CLIENTS AND HOSTS

**NOTE**: If you accessed this from another platform, like Reddit, ensure you have the latest version for optimal performance. All versions are available.

**Primary Feature:**
* Ping Determination

**Optional Features:** 
* Double-click to lock/unlock the overlay for easy dragging
* Shift + Left Click on a player, highlighted in a darker color for current selection, to toggle to BLOCKED, LOVED, or revert to normal display
* To exit, locate the icon in your system tray near the clock, right-click, and select Exit.

## HOW TO INSTALL AND USE:
**System Requirements:**
* Latest Java Runtime available at [java.com/en/download/](https://java.com/en/download/)
* Npcap from [nmap.org/npcap/](https://nmap.org/npcap/) (during installation, check "Install Npcap in WinPcap API-compatible Mode") 
   - For advanced users: Add %SystemRoot%\System32\Npcap\ to PATH instead.

Simply double-click the MLGA.jar file to run.

**NOTE:** If needed, right-click the JAR file, select Properties, and choose Unblock if "Unblock" appears below Attributes.

**If UAC is enabled:** 
You may need to run the application via Command Prompt due to PCap4J library limitations in finding devices.
* Copy the folder path where MLGA is located (e.g., C:\Users\Dwight\Desktop\MLGA\)
* Right-click in the same directory as MLGA, create a new text document
* Open with Notepad, type: cd C:\The\Path\You\Copied\Earlier
* Start a new line, type: javaw -jar MLGA.jar
* Save As MLGA.bat (select "All Files")
* Right-click the batch file, Run as Administrator

## HOW TO SUBMIT A DEBUG LOG
* Right-click in the same directory as MLGA, create a new text document
* Open with Notepad, type: java -jar MLGA.jar
* Save As MLGADebug.bat (select "All Files")
* Right-click the batch file, Run as Administrator
* Submit a picture or copy of the text to an Issue