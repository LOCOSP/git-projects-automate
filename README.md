# bash-automate-gitlab-new-project

Simple bash script that's create new gitlab project  and clone created project to same named folder on local machine in seconds.

# Installation

1. Clone to directory of choice:

        git clone https://gitlab.websafe.pl/bmilewski/bash-automate-gitlab-new-project.git

2. Give permissions to ```automatelab``` and ```automatehub``` file 

        chmod +x automatelab
        chmod +x automatehub

3. Copy ```.automate``` file into home directory.
4. Edit ```.automate``` file.

Done.

# Usage

To run script navigate to script directory and type if the project should be created on GitLab

        ./automatelab [ new project name ] 

and if should be created on GitHub

        ./automatehub [ new project name ]

To use the script globally create link in ```/usr/bin``` (as root):

        ln -s /full/path/to/automatelab /usr/bin
        ln -s /full/path/to/automatehub /usr/bin

after that You can call ```automatelab [ new project name ]``` for GitLab project and ```automatehub [ new project name ]``` for GitHub project form any directory You are.