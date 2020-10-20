# win10script
This is the Ultimate Windows 10 Script from a creation from multiple debloat scripts and gists from github. I also added Chocolatey and other tools to the script that I install on every machine. This is a version that's been personalized for my own taste! Use at your own risk. Mean't to be ran on a fresh install of Windows 10.

## My Additions
- Dark Mode!
- Chocolatey Install
- Uninstalling OneDrive!
- O&O Shutup10 CFG and Run
- Added Debloat Microsoft Store Apps
- Added Programs:
	- Google Chrome
	- VS Code
	- Python 3
	- K-Lite Full (might be redundant with MPC)
	- MPC
	- 7Zip

## Modifications
I encourage people to fork this project and comment out things they don't like! Here is a list of normal things people change:
Comment any thing you don't want out... Example:

```
########## NOTE THE # SIGNS! These disable lines This example shows UACLow being set and Disabling SMB1
### Security Tweaks ###
	"SetUACLow",                  # "SetUACHigh",
	"DisableSMB1",                # "EnableSMB1",

########## NOW LETS SWAP THESE VALUES AND ENABLE SMB1 and Set UAC to HIGH
### Security Tweaks ###
	"SetUACHigh",
	"EnableSMB1",
```
