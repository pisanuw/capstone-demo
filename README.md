# CSS 342 / 343 Docker Demo

## Purpose
This repository is intended to support you practicing using your Docker container and Google Test to use TDD to complete your assignments. 
Completing this should prepare you to know what to do for your next full assignment.

## Part A Steps - Once per opening (skipping steps here is often possible on repeated re-opening). Pay close attention to steps 3-5.
1. Follow 1-time Setup Instructions (if you have not yet)
    1. [Setup Repo](https://github.com/Jeffcaruso/capstone-Setup_Repo) 
1. Open up your container that has been setup (skip if already open) 
    1. Docker - start the container you made from containers page of docker desktop
    1. Remote Explorer (VSC) - find the container with the play button icon ![images/play button.png](https://github.com/Jeffcaruso/capstone-Setup_Repo/blob/main/images/play%20button.PNG)
        1. Note, you may need to select 'dev container' from the drop down menu.
        2. Then scroll/look down to the other containers section looking for that play button.
        ![images/drop down.png](https://github.com/Jeffcaruso/capstone-demo/blob/main/images/drop%20down.PNG)    
    1. Open the container (pick either A or B)
        1. Same window - press arrow; ->
        1. New window, the window with a + in corner; +[]
        ![images/showing opening](https://github.com/Jeffcaruso/capstone-Setup_Repo/blob/main/images/showing%20area%20selected.png)
    1. Wait for loading (probably will say something like 'starting container'or 'starting dev container' and have a loading bar)
1. Clone the repo e.g.,'git clone https://github.com/Jeffcaruso/capstone-demo.git'
1. Use Bash terminal 'ls -alh' and 'cd (dir to move to)' to navigate to the root of the github repo
    1. I.e., A/B/C/<Repo_Name>
    2. E.g., /home/cssuwbstudent/UWnetid/capstone-demo; Where capstone-demo is the repo name for the project.
    3. Note, In most cases, this means you will end up only needing to 'cd' into the github repo itself once downloaded.
1. Use Bash terminal 'code .' which will reopen vsc in that folder (This automatically updates your workspace so debugging can work)


## Steps to Run tests (locally) - doing these every time you want to run/test your new code
1. Write your code in the code files (*.cpp, *.h, etc...)
1. To Run, Enter command in bash terminal: ./runit.sh
    1. If it fails to run, Enter command in bash terminal: 'chmod +x runit.sh' 
1. To Debug, use the VSC menu:
    1. RUN > Start Debugging (F5)
    2. If it asks you to select a debugging mode / script, use "C/C++: g++ build and debug files"
        1. If it does ask, is should only ask you this the first time debugging this repo.

## Steps to Commit to GitHub with VSC
### Prerequisite: you have already 'git cloned' and 'code .' properly
1. Make changes to commit, view changes in the source control ![images/source control](https://github.com/Jeffcaruso/capstone-demo/blob/main/images/source%20control.PNG) tab of VSC
2. Enter a commit message
3. Press 'commit'
4. Press yes on the 'There are no staged changes to commit' dialog box.
    1. This will stage all changes and commit them directly   
6. Press 'Sync Changes'
7. Press OK to the "This action will push and pull commits from and to origin/main" dialog box
8. Your code will be pushed to github

## Steps of tracking VSC GitHub Actions Autograder
1. Follow previous steps to commit to the GitHub repo 
1. Navigate in a browser to see the repo page
1. There will be a yellow circle while the tests are running to the right of your commit message
    1. ![images/actions status.png](https://github.com/Jeffcaruso/capstone-demo/blob/main/images/actions%20status.PNG)
    2. Note, in some browsers, the yellow circle may not automatically update, if it has been more than about 1 minute and it is still not green, try refreshing the page.
1. There once testing completes there will either be a:
    1. Red X
    2. Green check
1. In any case - Yellow, green, or red you can click on it to open a summary view, then click details so see a detailed view like below
    1. Summary view
        1. ![images/summary view.png](https://github.com/Jeffcaruso/capstone-demo/blob/main/images/summary%20view.PNG)
    3. Detailed view
        1. ![images/detailed view.png](https://github.com/Jeffcaruso/capstone-demo/blob/main/images/detailed%20view.PNG)



