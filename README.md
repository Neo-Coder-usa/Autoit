SUPER DUCKHUNT WinDuck BETA (1.0 C-BETA) CONCEPT (Autoit Version, Win 32Bit)
by Neo_Nemesis (aka coderusa)

MAIN RUN FILE: IRC-SCRIPT.au3

This is a very rough draft of a Autoit DuckHunt IRC Bot. It works but has some issues that need to be worked out.

DuckHunt commands: https://codeusa.000webhostapp.com/duckhunt/duckhunt1-0autoit.htm

Channel OP Commands:
  !topic <topic info here> - changes topic of the channel
  !kick <user>
  !ban <user>
  !unban <user>
  !kickban <user>
MODES
  !op - +o if user is botmaster/access
  !op <username> - +o to another user
  !deop, !voice and !devoice are the same

SCRIPT AND BOT CONFIGURATION
Have all files in same folder, IRC-VARS.au3, IRC-SCRIPT.au3, Frankenstein.au3, IRC-BOT.au3
The script will create a duckhunt.ini file to store player stats

CONFIGURING BOT:
Configuration should be done in IRC-VARS.au3. Input server, port, channels, botname and botmasters. (Make sure you list yourself as the botmaster)
There are other settings in IRC-VARS.au3 that effect various aspects of the game.

RUNNING THE BOT:
Run the script in SciTe (or code editor), running from IRC-SCRIPT.au3
