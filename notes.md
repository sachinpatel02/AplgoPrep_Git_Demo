
# install

# setup
# check git version to confirm installation
    ```bash
        git --version
    ```

# list of config
    * git config --list --> check the config list
    * check username and email which is associated with Github
    * add username and email if not present already

    ```bash
        git config --list
        git config --global user.name "sachinpatel02"
        git config --global user.email "sachinp1613@gmail.com"
    ```



# Git workflow
* Create empty git repository without any history will be create when we inititate git init

    ```bash
        git init
    ```
# to add the snapshot of file to the staging area
    ```bash
        git add filename
    ```
# to check the changes in file (difference between working area and staging area)
    ```bash
        git status
    ```
# Git has three areas where it stores the data
* Working directory --> current changes
* Intermediate area or staging

# to ignore some files
* create a file .gitignore and add files which you don't want to be tracked
    ` .gitignore` : add files which need to be ignored

# add all the files to the staging area:
    ```bash
        git add . 
    ```
# Repository (Repo)
    > Location to store projects including all the files and history of their changes
    It will save all the changes, time, author details and we can revert back to any unwanted changes

    ```bash
        git commit -m "remarks - to explain changes"
    ```
    --doing another changes and using below to see the list of  commits

    ```bash
        git log
    ```
# revert back to previous commits

* `git chackout #hashcode` --> to go back to the previous changes
* `git checkout main` --> to come back to the current channges or latest commit which is called Head.
* `git branch` --> to check the current branch name

======================================
# pusing code to the GitHub

--> create reposioty in GitHub and then we can push the code to it

* `git remote add origin https://github.com/sachinpatel02/AplgoPrep_Git_Demo.git` --> adding remote url

* `git branch -M main` --> going to main branch

* `git push -u origin main` --> pushing to github
