# LOL Report Tool
[![version](https://img.shields.io/github/v/release/SivWatt/LOL_report_tool)](https://github.com/SivWatt/LOL_report_tool/releases)
[![Build Status](https://github.com/SivWatt/LOL_report_tool/actions/workflows/python-checks.yaml/badge.svg?branch=master)](https://github.com/SivWatt/LOL_report_tool/actions/workflows/python-checks.yaml)  
This tool automatically reports players after a game at statistic window in __League of Legends__.  
It is written in __Python 3.7__, and __pyautogui__ does most of the work.  

## Download
Go to [Release](https://github.com/SivWatt/LOL_report_tool/releases/latest) page and download __LeagueReport.zip__.

## Usage
Run `League.exe` as __administrator__ and the GUI will show.  
![GUI](/doc/info.PNG?raw=true)
  - Press `TEAM` to report __ALL__ of the players in your team  
  - Press `ENEMY` to report __ALL__ of the players in opponent team  
  - Press `ALL` to report literally all players except yourself  

The report message is copied from `reportText.txt`.  
User can modify the content to whatever he wants to meet his need.  
_Note that modifying `reportText.txt` takes effect after next time you restart `League.exe`_

## Supported Modes
Currently, this tool recognizes game mode image on the upper-left corner of __League of Legend Client__ window.  
If the game mode image is not included, it won't start reporting players.  
### Supports
- ARAM
- Nexus Blitz

## Troubleshooting
Most of the problems users come into are about images recognizing.  
You can take a look at `debuglog.log` to see which image the tool mismatches.  
And for image issues, it can simply be fixed by replacing image with screenshoted one by user himself/herself.

## Development
If you encounter any problem, feel free to let me know via creating [issues](https://github.com/SivWatt/LOL_report_tool/issues).
