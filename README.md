# Git Fork Demo
Weber State University's accompanying repository for the Forking a Repository in GitHub tutorial video. In this video, you will create your own copy of a repository by forking it, merge changes from the original repository by syncing your fork, and create a fork with a single command using the GitHub CLI.
## Forking and Cloning a Repository
1. Navigate to the repository you wish to fork on GitHub.
2. Click the "Fork" button, and select "Create fork."
3. With your fork open, click the green "Code" button to copy the repository URL.
4. Use `git clone` in your terminal followed by the repository link to clone the repository.
## Syncing Upstream Changes
1. Go to your fork's page on GitHub.
2. Click the "Sync fork" button, and select "Update branch."
3. Pull the changes to your local repository with `git pull origin main`.
## Alternative Method - GitHub CLI
1. Install GitHub CLI and configure it with `gh auth login`.
2. Use the command `gh repo fork owner-name/repository-name` to fork, clone, and configure the local repository.
3. Sync changes to your fork with the command `gh repo fork owner-name/repository-name`.
