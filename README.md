# COPR-repository-listing
Enables the copr repo if not enabled already and lists all the available packages in it 

repoList

A Bash script to list packages in a Copr repository.

Description

This script enables a specified Copr repository and lists all packages available in it. If the repository is not already enabled, the script will enable it.


Usage:

sudo repoList <repository_name>(format : username/repository_name)

Requirements

- Bash shell
- copr command-line tool
- dnf package manager
- jq JSON processor

Installation

1.(optional)works without adding to path but perferable

  Option 1: Move to /usr/local/bin

    1. Copy the script: sudo cp repoList /usr/local/bin/
    2. Make it executable: sudo chmod +x /usr/local/bin/repoList

  Option 2: Move to ~/.local/bin (recommended for personal use)

    1. Create the directory: mkdir -p ~/.local/bin
    2. Copy the script: cp repoList ~/.local/bin/
    3. Make it executable: chmod +x ~/.local/bin/repoList
    4. Add ~/.local/bin to your PATH: Add the following line to your ~/.bashrc file: export PATH=$PATH:~/.local/bin

Pull requests and issues are welcome!

License

GPL-3.0 license 

Author

Chinmay Malik

