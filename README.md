## Initialize your git repository:
- git clone <repo url>
- cd <main dir>
- mkdir README.md
- git commit -m "<commit msg>"
- check branch 
- git push -u origin <branch_name>


## DVC setup:
- pip3 install dvc
- dvc init

- mkdir <data> and add datasets in data folder
- dvc add data/.
- dvc remote add <remote_name> <https://dagshub.com/{user_name}/{repo_name}.dvc>
- dvc remote modify <remote_name> auth basic
- dvc remote modify <remote_name> user <user_name>
- dvc remote modify <remote_name> password <your_token>

- git add .
- git commit -m "<commit_msg>"
- git push

- dvc push -r <remote_name>
