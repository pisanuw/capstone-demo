# CSS 342 / 343 Docker Demo

## Purpose
This repository is intended to support you practicing using your Docker container and Google Test to use TDD to complete your assignments. 
Completing this should prepare you to know what to do for your next full assignment.

## Part A Steps - Once per opening (skipping steps here is often possible on repeated re-opening). Pay close attention to steps 3-5.
1. Follow 1-time Setup Instructions (if you have not yet)
    1. [Setup Repo](https://github.com/Jeffcaruso/capstone-Setup_Repo) 
1. Open up your container that has been setup (skip if already open) 
    1. Docker - start the container you made from containers page of docker desktop
    1. Remote Explorer (VSC) - find the container with the play button icon
    ![images/play button.png](https://github.com/Jeffcaruso/capstone-Setup_Repo/blob/main/images/play%20button.PNG)
    Note, you may need to select 'dev container' from the drop down menu
    ![images/drop down.png](https://github.com/Jeffcaruso/capstone-demo/blob/main/images/drop%20down.PNG)
    Then scroll down to the other containers section looking for that play button
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
