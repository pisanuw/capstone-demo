# CSS 342 / 343 Docker Demo

## Purpose
This repository is intended to support you configuring your Docker container to use Google Test to support your Test Driven Development

## Reminder, Steps for you to follow to open for Setup
1. Follow Setup Instructions (if you have not yet)
1. Open up your container that has been setup (skip if already open) 
    1. Docker - start the container you made from containers page of docker desktop
    1. Remote Explorer (VSC) - find the container with the play button icon
    ![images/play button.png](https://github.com/Jeffcaruso/capstone-Setup_Repo/blob/main/images/play%20button.PNG)
    1. Open the container (pick either A or B)
        1. Same window - press arrow; ->
        1. New window, the window with a + in corner; +[]
        ![images/showing opening](https://github.com/Jeffcaruso/capstone-Setup_Repo/blob/main/images/showing%20area%20selected.png)
    1. Wait for loading (probably will say something like 'starting container' and have a loading bar)
1. Clone the repo e.g.,'git clone https://github.com/Jeffcaruso/capstone-demo.git'
1. Use Bash terminal 'ls -alh' and 'cd (path)' to navigate inside the root of the github repo
1. Use Bash terminal 'code .' which will reopen vsc in that folder (This updates your workspace so debugging can work)


## Steps to Run tests (locally)
1. Enter command in bash terminal: 'cd capstone-demo/'
    1. If not already here. You want to be in same folder as the code files for this repo.
1. Write your code in the code files (<whatever>.cpp, <whatever>.h, etc...)
1. To Run, Enter command in bash terminal: ./runit.sh
    1. If it fails to run, Enter command in bash terminal: 'chmod +x runit.sh' 
1. To Debug, VSC menu:
    1. RUN > Start Debugging (F5)
    2. Pre existing configuration
    3. *** Not fully working yet (as of 2/13). Running works fine, getting debugging to work reliably, not completed yet...
