# Automate Your workflow creating new project environment in seconds

Simple bash script that's create new gitlab or github project and clone created project to same named folder on local machine.

# Installation

1. Clone to directory of choice:

        git clone https://github.com/LOCOSP/git-projetcs-automate.git

2. Give permissions to ```automatelab``` and ```automatehub``` file 

        chmod +x automatelab
        chmod +x automatehub

3. Copy ```.automate``` file into home directory.
4. Edit ```.automate``` file.

Done.

*Mac users if wnat to use VS Code as a editor, may have one more step to do

5. Install Code in PATH
- Launch VS Code.
- Open the Command Palette (⇧⌘P) and type 'shell command' to find the Shell Command: Install 'code' command in PATH command.

# Usage

To run script navigate to script directory and type if the project should be created on GitLab

        ./automatelab [ new project name ] 

and if should be created on GitHub

        ./automatehub [ new project name ]

To use the script globally create link in ```/usr/bin``` (as root):

        ln -s /full/path/to/automatelab /usr/bin
        ln -s /full/path/to/automatehub /usr/bin

after that You can call ```automatelab [ new project name ]``` for GitLab project and ```automatehub [ new project name ]``` for GitHub project form any directory You are.
