# iNeuron Github tasks
Repository showcasing the tasks assigned for learning the basics of git and github

1. [Task 1 - Basic Git Commands](#task-1---basic-git-commands)
2. [Task 2 - Create Repository](#task-2---create-repository)
3. [Task 3 - Handling Code Changes](#task-3---handling-code-changes)

### Task 1 - Basic Git Commands

| Command | Description | Screenshot |
| --- | --- | --- |
| git init | Initializes a folder as a git repository for tracking changes | [View](/images/git_init_screenshot.png) |
| git config | Used to set up the git configurations like username, password, etc. at global or local level | [View](/images/git_config_screenshots.png) |
| git remote add origin <remote git repo url> | Used to link a local repository to its corresponding remote repository| [View](/images/git_remote_add_origin_screenshot.png) |
| git status | Used to get the current status of files and folders in the repo | [View](/images/git_status_screenshot.png) |
| git branch | Used to list the available branches. By doing "git branch \<branch name\>" we can create a branch . By adding flags (-m (moving), -d (delete)) we can perform moving,deleteing of branches too | [View](/images/git_branch_screenshot.png) |
| git checkout | Used to switch to the specified branch | [View](/images/git_checkout_screenshot.png) |
| git pull | Used to pull the remote repository to the local branch | [View](/images/git_pull_screenshot.png) |
| git add | Used to add changes to the staging area | [View](/images/git_add_screenshot.png) |
| git commit | Used to commit the changes making them ready to be pushed to the remote repository | [View](/images/git_commit_screenshot.png) |
| git push | Used to push the commited changes to remote repository | [View](/images/git_push_screenshot.png) |
| git log | Lists the version history for a branch or for a specified file | [View](/images/git_log_screenshot.png) |
| git diff | Displays the difference in content between two branches | [View](/images/git_diff_screenshot.png) |
| git show | Used to display the metadata and changes associated with a specified commit | [View](/images/git_show_screenshot.png) |
| git merge | Used to merge a specified branch with the current branch | [View](/images/git_merge_screenshot.png) |
| git stash | Used to take our uncommitted changes (both staged and unstaged), saves them away for later use, and then reverts them from your working copy | [View](/images/git_stash_screenshot.png) |

### Task 2 - Create Repository

1. <b>Create an open source repository with proper project structure </b> <br><br>
Click this [link](https://github.com/Vibes1209/datascience-project-template/tree/main) to view the repository

2. <b>Create a detailed README.md file for the above repository </b> <br><br>
Click this [link](https://github.com/Vibes1209/datascience-project-template/blob/main/README.md) to view README.md for the newly created repo

3. <b>Add 2 collaborators to the repo </b><br>

* Sending invite and awaiting response <br><br>
![Invite Pending Image](/images/collaborators_invite_pending.png "Invite Pending Image")<br>

* After accepting Invite <br><br>
![Invite Accepted Image](/images/collaborators_invite_accepted.png "Invite Accepted Image")<br>

4. <b>Host a project page in Github Pages </b><br><br>
Project Page containing contact info hosted on Github Pages is available [here](https://vibes1209.github.io/datascience-project-template) <br><br>
![Project Page Image](/images/github_pages_screenshot.png "Project page hosted on Github Pages")

### Task 3 - Handling Code Changes

1. <b>Create an Issue in the repository</b> <br><br>
Issue created from the github repository <br><br>
![Issue Created Image](/images/create_issue_screenshot.png "Issue Created in the repo")

2. <b>Create a Pull Request for the above issue</b> <br><br>
Pull request created along with linking the issue <br><br>
![Pull Request Created Image](/images/pull_request_for_issue.png "PR created for the issue")

3. <b>Merge the Pull Request </b><br><br>
Pull request was merged with the main branch <br><br>
![PR Merged Image](/images/merge_request_successful.png "Merge was successful")

4. <b>Reject a Pull Request with comments </b><br><br>
Pull request is reviewed and closed without merging the commits <br><br>
![PR Merge rejected](/images/rejecting_pr_screenshot.png "PR closed without merging")

5. <b>Add dependabot alert and notify the owner for vulnerability </b><br><br>
Dependabot alert is enabled and notifications are configured <br><br>
![Dependabot Alert Enabled](/images/dependabot_alert_enabled.png "Dependabot Alert Enabled")

6. <b>Stash changes in a branch </b><br><br>
Use git stash to temporarily shelve changes in a branch and revert them later with ```git stash pop``` or ```git stash apply``` <br><br>
![Stashing Changes](/images/git_stash_screenshot.png "Stash changes with git stash")

7. <b>Create a new release for the project </b><br><br>
Created initial release with version v0.1.0 <br><br>
![Initial Release](/images/release_screenshot.png "Initial Release Created")

8. <b>Set up Project Board for the project </b><br><br>
* Github Project Board is created<br><br>
![Project Board Image](/images/projectboard_screenshot.png "Project Board created") <br><br>
* Project Board is now linked to the repo <br><br>
![Project Board Added Image](/images/projectboard_added_to_repo.png "Project Board added to repo")
