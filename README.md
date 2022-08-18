# -CMPG323-Overview---31602894-

#Repository :
I will be creating  repository for each project from project 1-project 5

Project 1( I already create repository for project 1)

Project 2

Project 3

Project 4

Project 5

#Diagram explaining project and repository context and how they are integrated

Because this project will be linked to a kanban project, the diagram will look like this:


#Branching Strategy to be used within each project :
I will be using GitHub Flow Branch Strategy -GitFlow, which is considered a bit complicated and advanced for many of today's projects, allows developers to work separately from the master branch on features where a feature branch is created from the master branch.

When the changes are finished, the developer merges them back into the master branch for release.

The following branches comprise this branching strategy

Master

Develop

Feature- to create new features that stem from the develop branch

Release- aids in the preparation of a new production release; typically branched from the develop branch and must be merged back into both the develop and master branches.

Hotfix- Like release branches, hotfix branches are created in response to a bug that has been discovered and must be resolved;

 #use of a .gitignore file within each project
gitignore file tells Git which files to ignore when committing your project to the GitHub repository. gitignore is located in the root directory of your repo.

#explain the storage of credentials and sensitive information

Never store credentials and sensitive data on GitHub:
GitHub’s purpose is to host code repositories. Beyond the permissions you set on your account, there is no other method of security that will ensure that your secret keys, private credentials, and sensitive data remain within a controlled and secured environment.
 
REFERENCES
[credentials and sensitive ](https://spectralops.io/resources/how-to-choose-a-secret-scanning-solution-to-protect-credentials-in-your-code/)

[branching strategy](https://www.flagship.io/git-branching-strategies/)
 
