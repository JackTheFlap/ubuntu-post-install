WSL Ubuntu Post Install Script
==========================

Version: 15? - JackTheFlap's Takeover

License: GPLv3

Original source can be found at https://github.com/snwh/ubuntu-post-install.

You can get the latest version from the git repository:

    git clone https://github.com/JackTheFlap/ubuntu-post-install.git

## Usage:

Run from source folder:

    bash ubuntu-post-install-script.sh

By adding the path of the script to your .bashrc you can run it anytime from a terminal
	
	export PATH=${PATH}:$HOME/<path-to-ubuntu-post-install-script>/


## About Forked Project:

This project was forked by myself with the intention to convert the ubuntu-post-install script into a WSL post-install script. I tend to run 2-3 WSL instances (Ubuntu WSL2, Alpine WSL1) and wanted to create a script to automate this process. Turns out forking an existing project was easier...

To start with I will focus on the Ubuntu WSL instance but will also include alpine-post-install eventually. Uses my wsl-dot-files project as a template for .zshrc and .bashrc changes - https://github.com/JackTheFlap/wsl-dot-files

## Original About:

Ubuntu Post Install Script is a simple bash script for automating the reconfiguration of a fresh Ubuntu installation –installing favourite applications, setting up configurations, etc. 

It is compatible with both 32 and 64 bit architectures

Feel free to copy, improve and distribute.
