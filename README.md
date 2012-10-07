This is a simple collection of small configuration files for various programs that I use regularly. Most of it is pretty uninteresting, but might be useful for those who are too lazy to make their own configuration files. 

Usage:
Clone this repository to any place you like, and then run "chmod +x setup && . setup", which will make the setup script executable and run it. This will make a set of hard links to the necessary locations in your home directory. It won't link if you already have the specified configuration files.

Notes:
The .bash_profile only contains a short line to make sure that the .bashrc is loaded for the login shell. You can probably ignore it for most systems unless you log into a command shell instead of a gui.

The .vimrc file constains some lines which are commented out. This is likely because they are plugin-specific key bindings or configurations. If you have the plugins, then feel free to uncomment them if you want the keybindings.
