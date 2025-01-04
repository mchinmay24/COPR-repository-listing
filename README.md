# COPR-repository-listing
Enables the copr repo if not enabled already and lists all the available packages in it 

repoList

A Bash script to list packages in a Copr repository.

Description

This script enables a specified Copr repository and lists all packages available in it. If the repository is not already enabled, the script will enable it.

Usage


bash
sudo repoList <repository_name>
(it will enter root user's shell so you need to exit it for output to be printed)



Replace <repository_name> with the name of the Copr repository you want to list packages for, in the format username/repository_name.

Requirements

- Bash shell
- copr command-line tool
- dnf package manager
- jq JSON processor

Installation

1. Copy the repoList script to a directory in your system's PATH (e.g., /usr/local/bin or ~/.local/bin).
2. Make the script executable with chmod +x repoList.
3.(optional)works without adding to path but perferable

Option 1: Move to /usr/local/bin

1. Copy the script: sudo cp repoList /usr/local/bin/
2. Make it executable: sudo chmod +x /usr/local/bin/repoList

Option 2: Move to ~/.local/bin (recommended for personal use)

1. Create the directory: mkdir -p ~/.local/bin
2. Copy the script: cp repoList ~/.local/bin/
3. Make it executable: chmod +x ~/.local/bin/repoList
4. Add ~/.local/bin to your PATH: Add the following line to your ~/.bashrc file: export PATH=$PATH:~/.local/bin

Contributing

Pull requests and issues are welcome!

License

GPL-3.0 license 

Author

Chinmay Malik

