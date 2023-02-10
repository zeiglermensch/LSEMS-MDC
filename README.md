# LSEMS Duty MDC

## How to use:

> If you are having issues with it not working in game, you may have to run the file as administrator, as RAGE may be preventing it from capturing your keyboard input.

1. Download the entire repository (`Green` Button -> `Download Zip`).
2. Extract the zip file into a folder of your choosing.
3. Run the `LSEMS MDC.exe`

- If you have any issues with this menu or any bugs that you find, feel free to reach out to me.  Additionally, if you want new features added or want to add a feature yourself, feel free to reach out or do a push/pull request.
- Additionally, I have ran this by admins and they have all said that this does not break any rules, as it is all stuff that we do all the time.

### Variables:
> All variables in the `hotkeys.ini` file use AutoHotKey hotkey prefixes found [here](https://www.autohotkey.com/docs/v1/KeyList.htm).

| File | Variable | Description | Usage |
| ----------- | ----------- | ----------- | ----------- |
| hotkeys.ini | StartMDC | Key or combo to start displaying the GUI | Toggle |
| hotkeys.ini | StopMDC | Key or combo to stop displaying the GUI | Toggle |
| hotkeys.ini | PayToll | Key or send `/paytoll` | Press key |
| hotkeys.ini | ToggleMouse | Key to enable mouse interaction with the GUI | Toggle |
| hotkeys.ini | CheckUnits | Key to send `/units` | Press key |
| hotkeys.ini | CheckCalls | Key to send `/calls` | Press key |
| hotkeys.ini | QuitApplication | Key to quit the application | Press key |
| hotkeys.ini | AFKAddition | Key to send `/afkmath [input]` | Press key > enter first number > press `enter` > enter second number > press `enter` |
| hotkeys.ini | RespondCall | Key to send `/resp [input]` | Press key > enter call ID > press `enter` |
| hotkeys.ini | SetCall | Key to send `/setcall [input]` | Press key > enter call ID > press `enter` |
| hotkeys.ini | CloseCall | Key to send `/closecall [callID]` | Press the key after you have responded to or set a call |
| hotkeys.ini | LeaveCall | Key to send `/setcall -1` | Press key |
| hotkeys.ini | MDtoPD | Key to send `/deplow MD to PD ` | Press key |
| hotkeys.ini | MDtoSD | Key to send `/deplow MD to SD ` | Press key |
| hotkeys.ini | MDtoDOC | Key to send `/deplow MD to DOC ` | Press key |
| hotkeys.ini | MainHelp | Key to open the help dialogue | Press key |
| hotkeys.ini | TreatmentGui | Key to open the treatment GUI | Press key |
| hotkeys.ini | LowerRaiseBasket | Key to lower and raise the left and right basket for you whirly bird people | Press key |
| hotkeys.ini | ResetBaskets | Key to reset the basket positions for you whirly bird people | Press key |
| variables.ini | Callsign Letter | Letter of your callsign | N/A |
| variables.ini | Callsign Number | Number of your callsign | N/A |
| variables.ini | Vehicle Ambulance | `/fspawn` name of the ambulance you use | N/A |
| variables.ini | Vehicle Scout | `/fspawn` name of the scout you use | N/A |
| variables.ini | Vehicle Maverick | `/fspawn` name of the maverick you use | N/A |
| variables.ini | Vehicle Kamacho | `/fspawn` name of the Kamacho you use | N/A |
| variables.ini | Vehicle Firetruck | `/fspawn` name of the firetruck you use | N/A |
| variables.ini | Vehicle Access Scout | Enable or disable the button to spawn the scout | `True` or `False` |
| variables.ini | Vehicle Access Kamacho | Enable or disable the button to spawn the kamacho | `True` or `False` |
| variables.ini | Vehicle Access Firetruck | Enable or disable the button to spawn the firetruck | `True` or `False` |
| variables.ini | Vehicle Access Maverick | Enable or disable the button to spawn the maverick | `True` or `False` |
| variables.ini | Sex 2 | Third person of your character | N/A |
| variables.ini | Sex 3 | Third person possessive of your character | N/A |
| variables.ini | Debug Value | Enable this to have it type into notepad, rather than rage | `True` or `False` |

### MDC Overview:
- `Call Sign Box`: Used as a display for the unit you are currently in and to join a custom unit.
- `C`: Used as the create unit button.
- `R`: Used as the rename unit button.
- `J`: Used as the join unit button.
- `L`: Used as the leave unit button.
- `D`: Used as the Disband unit button.
- `Trans Box`: Used as a display for the type of vehicle you will spawn or are going to spawn.
- `A`: Used to spawn an Ambulance.
- `Sc`: Used to spawn a Scout.
- `K`: Used to spawn a Kamacho.
- `F`: Used to spawn a Firetruck.
- `M`: Used to spawn a Maverick.
- `P`: Used to `/delambulance`.

Credit to `DBAGs Crux`, the original creator of this modified menu.

# Troubleshooting Common Issues:

| **Problem** | **Solution** |
|:-----------------------------------------------------------------:|:-----------------------------------------------------------------:|
| The GUI is not showing up in game | Ensure that you are running the AHK script as administrator. |
| The GUI minimizes my game every time I open it | Ensure that you are running your game in `Windowed Borderless` mode. |

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
