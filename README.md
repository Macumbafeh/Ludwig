# Ludwig with Pawn integrated
A BiS (best in slot) list addon for World of Warcraft TBC 2.4.3 based on [Ludwig 1.6.0](https://github.com/tullamods/Ludwig).

##Features
In addition of standard Ludwig features:
- Type filter multi-selection.
- List sorting by Pawn values (aka BiS list).

## Getting Started
### Installing:
1. Download and install [Pawn 1.1.2](http://tbcwowaddons.weebly.com/pawn.html) addon.
1. Copy "Ludwig" directory to "WoW\Interface\AddOns\" directory.
### Configuring:
1. Run WoW.
1. Configure Pawn:
    2. Open Pawn options (Character > `Pawn`). 
    2. Configure Pawn scales: import scales from [here](http://tbcwowaddons.weebly.com/pawn.html) 
    or create your own. More information about scales you can find in "WoW\Interface\AddOns\Pawn\Readme.htm" file.
    
## Running
1. Open Ludwig frame entering `/lw` command.
2. Set up filters for what items you look for. You can select multiple item types at the same time 
(e.g. Gem/Red and Gem/Orange).
3. Click `Pawn` and select a Pawn scale to sort the list.

## Commands
- `/lw` or `/ludwig` – Brings up the search frame
- `/lw <item name>` – Prints out a list in the chat window of the top 10 items matching <name>
- `/lw --pawn|<scale name>` – Sorts list of items by Pawn's values.
- `/lw --pawn` – Disables sorting.

## Known Issues
- Unfortunately, required version of Pawn works with English localisation only.
- Some items cannot be fully valued by Pawn and marked with an asterisk as Pawn does.
In general, these are items with procs and activation.
- Sorting large list freezes UI due to cache miss bug in Pawn code.
- The addon looks for items in WoW's cache so item that you have never seen will not present in the list. 

## Authors
* [tullamods](https://github.com/tullamods): 
    * [**Tuller (Jason  Greer)**](https://github.com/Tuller) – *original [Ludwig](https://github.com/tullamods/Ludwig)*
    * [**Jaliborc (João Cardoso)**](https://github.com/Jaliborc) – *original Ludwig*
* [Dawer](https://github.com/iDawer) – *Pawn integration for Ludwig*
