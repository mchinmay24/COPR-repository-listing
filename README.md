# COPR-repository-listing
Lists all the available packages in it and enables the repo on demand

A Bash script to list packages in a Copr repository.

Description

This script lists all packages available in a copr repository.

Usage:

repoList <repository_name>(format : username/repository_name) {for lisiting packages in a repository}

sudo repoList <repository_name>(format : username/repository_name) {for lisiting packages and enabling the repository as well}

Requirements

- Bash shell
- copr command-line tool
- dnf package manager
- jq JSON processor

Installation

1.(optional)works without adding to path but perferable

  Option 1: Move to /usr/local/bin

    1. sudo cp repoList /usr/local/bin/
    2. sudo chmod +x /usr/local/bin/repoList

  Option 2: Move to ~/.local/bin (recommended for personal use)

    1. mkdir -p ~/.local/bin
    2. cp repoList ~/.local/bin/
    3. chmod +x ~/.local/bin/repoList
    4. Add the following line to your ~/.bashrc file: export PATH=$PATH:~/.local/bin

Pull requests and issues are welcome!

License

GPL-3.0 license 

Author

Chinmay Malik

