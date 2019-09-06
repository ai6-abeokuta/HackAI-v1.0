# HackAI v1.0

## About Us 

AI Saturday Abeokuta is a community-driven study group created to promote
Artificial Intelligence in Abeokuta and train its members to become skilled in
the rapidly growing field of Artificial Intelligence.
AI Saturday Abeokuta is currently in its second cycle, and it has seen almost
double the number of members from the first cycle. The members of AI
Saturday Abeokuta are mainly students of tertiary institutions and fresh
graduates.

## The Hackathon
AI Saturdays Abeokuta is driven by the members desire to learn as many
things as possible in the broad field of Artificial Intelligence, and a hackathon
is one way to bring all of the acquired knowledge together, to create
something special.

The proposed title of the hackathon is “HackAI v1.0,” and the theme is "Creating AI Models That Solve Problems.” The goal of HackAI v1.0 is to have
developers with knowledge in the field of AI, create projects that provide
solutions to various problems through created Artificial Intelligence models.

## HackAI Work Flow
Every of the selected participant's are expected to have a good understanding of version Control Systems as well as a good understanding of git. 
As a participant, you're expected to do the below listed.

1. Create a private repository for your project.
2. Add us as a collaborator to your repository before your first commit. (Username: "ai6-abeokuta")
3. Wait for us to create a GitHub project which you will be added to. This helps us to monitor your work progress as you code. You can read more about github projects ![here](https://help.github.com/en/articles/about-project-boards)
4. Read our Version Control workflow below and adhere strictly to it.
5. Go ahead and start working on your projects.


### Version Control Workflow
Your projects progress is being tracked by the GitHub project we created for your team which is linked to your repository.
This makes it very important to adhere to a strict VC workflow. 

#### Base branch: `master`

#### Work branch: `develop`

To work on a new chore/feature/bug

- checkout to master
- pull from master remote
- checkout to new feature/fix/chore branch (git checkout -b feature/xxx-xxx or git checkout -b chore/setup)
- do your magic
- merge and commit changes on that branch (git add . && git commit -m "finished feature xxx")
- push branch to remote (git push origin feature/xxx-xxx)
- checkout to `develop` branch (git checkout develop)
- pull from develop remote (git pull origin develop)
- merge in new feature/fix/chore branch into `develop` (git merge feature/xxx-xxx)
- push `develop` to remote (git push origin develop)
- then, create pull request from `develop` to `master`

##### NOTE: No one should push to master, this is very important. Always create a pull request first and get it merged to master by your team lead
