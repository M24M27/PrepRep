# RepHub
PrepRep is a Bash script that automates the backup of your GitHub repositories. It fetches all repository names associated with your GitHub account, and then clones each repository into a specified directory. This is perfect for keeping local backups of all your work.
PreRep...Prepare Repos for worst case scenarios

## Requirements

- GitHub CLI (`gh`)
- `jq`
- GitHub personal access token

## Installation

1. Clone this repository: git clone https://github.com/yourusername/PrepRep.git
2. Navigate to the repository: cd PrepRep
3. Make the script executable: chmod +x PrepRep.sh


## Usage

1. Run the script: ./PrepRep.sh
2. Follow the prompts to enter your GitHub username and personal access token.
3. Specify the directory where you want to backup your repositories ( or choose current directory/ make a new dirctory ).

The script will then fetch all your repositories and clone them into the specified directory.

## Note

Make sure to create a personal access token on your GitHub account and grant the `repo` and `read:user` scopes. This token is necessary to access your repositories through the GitHub API.



