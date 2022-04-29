**mb-reset** is a simple helper script that can be helpful in some uncomfortable situations.

– you made a fatal mistake editing an important configuration file (rc.xml, autostart) and your system is not working as it should

– you are using the Mabox version installed long ago and you want to get newer versions of configuration files (for menu/panels, Conky, tint2 etc.)


mb-reset is a very simple script and all it does is copy the default files to the right place in your home directory.

Run the script from the user account (not root!). To see all options just type in the terminal:
```
mb-reset
 mb-reset - reset/update user config files to current defaults.
    It only affects files shipped with Mabox.
    Be aware that you may loose your own customizations (if any).

 Usage: mb-reset option

 Options:
   Compare mode:
     -c           - compare files using meld GUI (if installed)
                    It lets you see changes and decide which one to pick or not.
                    Works with rc.xml,bashrc and autostart files
                    Usage: mb-reset -c obrcxml | autostart | bashrc
   Overwrite mode:
     obrcxml      - rc.xml default OpenBox configuration file
     obautostart  - default autostart file
     bashrc       - bash config file (~/.bashrc)
     terminator   - terminator config
     conky        - overwrite conky config files in ~/.config/conky/
     tint2        - overwrite tint2 panel config files in ~/.config/tint2/
     jgthemes     - overwrite menu/sidepanels color schemes in ~/.config/mabox/jgobthemes/
     mainmenu     - overwrite main menu files (favorites.csv)
     leftpanel    - left panel custom commands
     rightpanel   - right panel custom commands
     logout       - logout dialog



```
