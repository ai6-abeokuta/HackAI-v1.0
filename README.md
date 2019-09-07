# HackAI v1.0

## About Us 

AI Saturdays Abeokuta is a community-driven study group created to promote
Artificial Intelligence in Abeokuta. It trains its members to become skilled in
the rapidly growing field of Artificial Intelligence.

## HackAI Work Flow
Every participant is expected to have a moderate understanding of the git Version Control System, and know how to use Github. 
As a participant, you're expected to do the following in order to get started.

1. Create a private repository for your project.
2. Add us as a collaborator to your repository before your first commit. (Username: "ai6-abeokuta")
3. Wait for us to create a GitHub project which you will be added to. This helps us to monitor your work progress as you code. You can read more about github projects [here](https://help.github.com/en/articles/about-project-boards)
4. Read the Version Control workflow below and adhere strictly to it.
5. Go ahead and start working on your project.


### Version Control Workflow
Your project progress is being tracked by the GitHub project we created for your team which is linked to your repository.
This makes it very important to adhere to a strict VC workflow. 

#### Base branch: `master`

#### Work branch: `develop`

To work on a new task/feature/bug

- checkout to master
- pull from master remote
- checkout to new feature/fix/task branch (git checkout -b feature/xxx-xxx or git checkout -b chore/setup)
- do your magic
- merge and commit changes on that branch (git add . && git commit -m "finished feature xxx")
- push branch to remote (git push origin feature/xxx-xxx)
- checkout to `develop` branch (git checkout develop)
- pull from develop remote (git pull origin develop)
- merge in new feature/fix/chore branch into `develop` (git merge feature/xxx-xxx)
- push `develop` to remote (git push origin develop)
- then, create pull request from `develop` to `master`

##### NOTE: No one should push to master, this is very important. Always create a pull request first and get it merged to master by your team lead.
