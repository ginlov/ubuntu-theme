# ubuntu_theme
Custom ubuntu top bar and theme.

# Prerequisite:
* powerline font

# Another theme:
* Theme for top bar with custom color and appearance.

# Icon theme blue:
* Icon theme with custom icon.

# .restartgnomeshell.sh
* Script fixing dash to dock extensions.
* Restart gnome shell service each time unlocking screen.

# .bashrc
* Customize bash prompt.
<img src="images/bash_theme.png" height="15"/>
<img src="images/bash_theme2.png" height="15"/>

# How to use:
* Copy folder anothertheme to .themes.
* Copy folder iconthemeblue to .icons.
* Replace your .bashrc file with this .bashrc or copy from FUNCTIONS to the end of file to your .bashrc.
* [Optional] If you use dash to dock extension: 
  * Copy .restartgnomeshell.sh to home/$USER directory.
  * Change mode to executable: ```sudo chmod +x /home/$USER/.restartgnomeshell.sh```.
  * Add ```/home/$USER/.restartgnomeshell.sh``` to startup applications for running it as a daemon.
