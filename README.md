# SolarCarTelemetry
Welcome to telemetry! This README file is intended to provide you with some general guidelines and basic Git commands to help you get started and ensure a smooth collaboration experience.
## Installing Windows Subsystem for Linux (WSL2) on windows 11
Start by opening Windows Powershell or Command Prompt as administrator.
Execute the following command:
```wsl --install```
Restart your computer to finish installation on Windows 11.

## Basic Git Commands
Git is a version control system that helps us manage our code and collaborate efficiently. Here are some basic Git commands for your reference:
### Cloning a Repository
To create a local copy of a remote repository, use the following command:
```git clone <repository_url>```
### Adding and Committing Changes
After making changes to your local code, you need to add and commit them to your local repository:
```
git add <file_name>  # Stage the changes
git commit -m "Your commit message"  # Commit the changes
```
### Pushing Changes
To upload your local changes to the remote repository, use the following command: 
```git push```

### Pulling Changes
To update your local repository with changes from the remote repository, use the following command:
```git pull```

### Branching
To create and switch to a new branch: ```git checkout -b <branch_name>```
To switch to an existing branch: ```git checkout <branch_name>```

### Merging
To merge changes from one branch into another: ```
git checkout <target_branch>  # Switch to the target branch
git merge <source_branch>  # Merge changes from the source branch
```
If conflicts occur during a merge, you will need to resolve them manually. Open the conflicted file, make the necessary changes, and then commit the resolved file.
