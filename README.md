 Git Branch Workflow Project
Master ➝ Main using Pull Request

This project demonstrates a proper Git workflow where:

 First, I created the master branch

 Pushed the code to GitHub

 Created a Pull Request from master to main

 Successfully merged it into main

This is part of my learning journey. 
#BhushanTechJourney

 Step 1: Initialize Git Repository
git init
 Step 2: Create and Switch to Master Branch
git checkout -b master

 Screenshot:

![Create Master Branch](./img/Screenshot%202026-03-02%20111355.png)
 Step 3: Add and Commit Files
git add .
git commit -m "Initial commit on master branch"

 Screenshot:

![Commit on Master](./img/Screenshot%202026-03-02%20111718.png)
 Step 4: Connect Remote Repository
git remote add origin https://github.com/your-username/your-repo-name.git
 Step 5: Push Master Branch to GitHub
git push -u origin master

 Screenshot:

![Push Master Branch](screenshots/push-master.png)
 Step 6: Create Pull Request (master ➝ main)

Steps:

Open repository on GitHub

Click Compare & Pull Request

Select:

Base branch: main

Compare branch: master

Click Create Pull Request

 Screenshot:

![Create Pull Request]( ./img/Screenshot%202026-03-02%20095615.png)
 Step 7: Merge Pull Request

Click Merge Pull Request
Confirm merge.

 Screenshot:

![Merge Pull Request](./img/Screenshot%202026-03-02%20111909.png)
 Branch Flow
master  ────────►  Pull Request  ────────►  main
 Project Structure
project-folder/
│── README.md
│── screenshots/
│     ├── create-master-branch.png
│     ├── commit-master.png
│     ├── push-master.png
│     ├── pull-request.png
│     └── merge.png
 Tools Used

Git

GitHub

 Author Bhushan Tayade
DevOps Learner | AWS Enthusiast 
