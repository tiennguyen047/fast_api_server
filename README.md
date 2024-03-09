# fast_api_app
This repo was created to learn RESTAPI and fast_api python

How to deploy fast_api server? Flow steps below
Step1:
    - Execute "make build_image" to build fast_api image with name "fast_api_python"

Step2:
    - Execute "make run_image" to start fast_api server
    - if user wants to restart container use "make rerun_startup"

*Note: User need to install Docker before deploy the fast_api server


…or push an existing repository from the command line
git remote add origin https://github.com/tiennguyen047/fast_api_server
git branch -M main
git push -u origin main
