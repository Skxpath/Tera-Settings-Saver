## Tera-Settings-Saver 2.0
Forked module - updated readme.md for easier understanding of how to use it. Mod will not be maintained in this fork (yet?)

Tera settings saver is a module for Tera-Proxy which stops your settings from getting reset, aswell as it allows you to easily transfer settings between characters/servers/region. Also for those spicy Caali proxy users, it's auto update compatible.

### How to use:
Command | Usage | Arguments
--- | --- | ---
key | Transfer settings from another character / lock your keybinds | File name / lock
set | Transfer settings from another character / lock your keybinds | File name / lock

For example, if you want to save the keybinds and settings for a character (named Kev):

**Key lock**

**Set lock**

This will save a file in proxy/bin/node_modules/Tera-Settings-Saver/data as "Kev-4107.json" for example.

Log onto character you want to transfer settings to (named Vic):

**Key Kev-4107**

**Set Kev-4107**

Relog into Vic and Kev's settings will be there now.

#### File name(s) can be found by going to proxy/bin/node_modules/Tera-Settings-Saver/data

### Bugs:
Can potentially reset a glyph & item set page if the settings has been reset(it will print in the chat)
