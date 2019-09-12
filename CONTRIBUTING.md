*Welcome, and thank you for contributing to this project. Please take your time to study this document carefully before making any changes to the codebase, to ensure you're on the same page with the rest of the team and we can all collaborate seamlessly.*   

# Workflow
This project uses the Fork & Pull Model for receiving contributions. Read about the Fork & Pull Model here.    
Your group leads will create a fork where all of your group's work will live. Individual contributions in each of these forks will be made according to the GitHub Flow. Read about it here. Group leads will be responsible for creating working branches for each memeber as tasks are assigned. This means that you'd usually have no reason to create a branch on your own.    

## Branch Structure
### Upstream
The main / original / upstream (hereinafter upstream) repository will have only two (2) branches. Deployment, and Integration. Additional hotfix branches may be created to work on critical bugs in the deployment.    
__The Integration branch__ is where features from the different forks are brought together. Group leads submit your pull request here. This is the default branch. An integration team will be responsible for bringing it all together resolving any possible merge conflicts that may arise.        
__The deployment branch__ does what it says. The code on this branch goes live to our hosting servers and must be kept in pristine condition. When the integration branch reaches a milestone, the deployment branch is updated via pull request.
__Hotfix branch.__ In the event that a bug slips past the integration team and makes it into deployment, a hotfix branch is created off of deployment. On completion, this branch is merged with deployment, and also with integration so the fixes are reflected in all future deployments.

### Forks
Each fork represents work on a specific feature or bugfix. A group is assigned a fork and works together to complete the feature. Forked repositories should be renamed to include a suffix with double underscores that describes what feature is being worked on. Example: workflow-test-repo__homepage.   
__Feature branch.__ Once a fork is created, a feature branch is made. This is where all of the group memebers' individual work is brought together. When the feature is completed, a pull request is made from this feature branch to the upstream integration branch. Feature branches are name with the "ft__" prefix, with double underscores, for easy identification. The branch name should correspond with the suffix added to the repository name. Example: ft__homepage.
__Working branch.__ This is where initial work gets done. The feature for a fork is broken down into small tasks which are distributed among group members. A branch is created for each group member to work on their task. The name of a working branch should correspond with the Slack display name of the person assigned to this task. Working branch names should begin with an "@" and all spaces should be replaced with a dash. Example: @Feranmi-Akinlade.

### Staying Updated
When work with others on the same codebase, sometimes others make changes that affect your work. While great care has been taken to create a modular team workflow to keep this to a minimum, merge conflicts are inevitable. It would _suck_ to finish working on a task or feature, only to find that the codebase has evolve and you need to rework everything to conform to the new changes. To manage this, each team member needs to make sure that at every given time, their working directory is up-to-date with the latest changes from the upstream integration branch. This is achieved with a two-fold process.
#### Group Leads - Pulling Upstream

#### All Team Members - Pulling Remote


## Code Structrure & Readability


