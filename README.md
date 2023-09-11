# Tutorial 01

**Course Title**: Web Development

**Course Code**: IRM1005 / ITEC1005

**Semester**: Fall 2023

**Due Date**: n/a

**Assessment**: n/a

## TLDR

1. Create your tutorial repository.
2. Download your tutorial code, make modifications to the `index` HTML file, and commit the changes back to your repo.
3. Turn on GitHub pages
4. Submit a comment in the show and tell discussion board and share a link to your live web page

## Description

The goal of this tutorial is for students to gain experience using GitHub Classrooms to accept an exercise, create a repository, download and update their code using VSCode on their local machine, submit code changes to GitHub, turn on GitHub Pages, and view their project home page both locally and live.

Students will also gain experience interacting with the class discussion board on GitHub, which will be a useful tool where students have the opportunity to post questions about their code throughout the semester.

## Table of contents

- [Instructions](#instructions)
- [Additional Help](#additional-help)
- [More about Git and GitHub](#octocat-git-and-github)
- [Additional Resources](#📚-additional-resources)

## Instructions

If you are reading this, you already have created a GitHub account and accepted the first tutorial which created this GitHub repository. Well done!

To complete this tutorial you must follow the steps below. Additional help can be found below for each step.

1. Install [Git](https://git-scm.com) on your machine
2. Configure Git on your machine
3. Install [VSCode](https://code.visualstudio.com) on your machine
4. Install the [LivePrevew](https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server) VSCode Extention
5. Clone your tutorial 01 repository
6. Find the `index.html` page in your local repository
7. Follow the commented instructions in the code and add the specified content to your home page as per instructions
8. Preview your home page on your local machine by using the LivePreview feature
9. Commit your changes
10. Push your commits to GitHub
11. Turn on GitHub Pages for your tutorial repository
12. View your live public home page
13. In the [Tutorial 01 - Show and Tell](https://github.com/orgs/irm1005-itec1005-fall-2023/discussions/2) discussion in our GitHub Discussion Group, add a comment with a link to your live home page
14. Check out some of your other team members pages

## Additional help

### GitHub student benefits

GitHub provides some great benefits for registered students. You do not have to register to the students program to complete the course, but it strongly recommended.

- [GitHub students program](https://education.github.com/students)
- [GitHub students registration](https://education.github.com/discount_requests/application)

### GitHub Codespaces

The list of [students benefits](https://education.github.com/pack#offers) is long and presents some great value, but perhaps the most valuable is access to 180 hours / month of [GitHub Codespaces](https://education.github.com/experiences/primer_codespaces).

This service allows you to do all of your code work in a web browser, and not have to install anything on your local machine. Depending on how you like to code this may be easier then setting up a local development environment.

### Installing Git

Git is the version control software that we will use throughout this course. You must have Git working on your local machine to submit to your code for assignments, as well as the midterm and final exams.

- [Git Homepage](https://git-scm.com)
- [GitHub's guide to installing Git](https://github.com/git-guides/install-git)
- [Atlassian's guide to installing Git](https://www.atlassian.com/git/tutorials/install-git)

### Configuring Git

Once installed on your local machine, you will need to configure Git with your identity.

In a command terminal enter the following commands (you don't type the dollar sign `$`), replace your name with your name and your email with the email you used to create your GitHub account.

```bash
$ git config --global user.name "John Doe"

$ git config --global user.email johndoe@example.com
```

### Installing VSCode

VSCode is an extremely popular open source code editor built by Microsoft, and recommened for this course. While all of the documentation for this course assumes that you are using VSCode, you are permitted to use any code editor that you are comfortable with.

Download and install VSCode by visiting the [VSCode download page](https://code.visualstudio.com/download) and selecting the installer for your maching.

- [VSCode homepage](https://code.visualstudio.com)
- [Getting started with VSCode](https://code.visualstudio.com/learn/get-started/basics)

### Installing LivePreview

The VSCode LivePreview extension sets up a local web server that we can use to preview our pages. This helps speed up our development process by providing developers with a near instant preview so they can see what their web page looks like as they write code.

Instructions on how to install and use the LivePreview extention are found below:

- [Download LivePreview extention](https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server)

<img alt="Screenshot 2023-08-17 at 10 48 43 AM" src="https://github.com/irm1005-itec1005-fall-2023/template-exercise-01/assets/9325038/cd66b651-8766-4038-baf7-754e7c98654a">

### Cloning your tutorial 01 repository

When your tutorial 01 repository was created, it was saved in the cloud. To work on your code, you will need to create a local copy that code that you can modify. This is referred to as "cloning".

The following are steps to clone your tutorial 01 repository and work with the code locally in VSCode.

#### Step 1: On GitHub.com, navigate to the main page of your tutorial 01 repository

#### Step 2: Above the list of files, click on the `Code` button

![image](https://github.com/irm1005-itec1005-fall-2023/template-exercise-01/assets/9325038/6de8b8db-91f8-4967-b650-6c6ee070220b)

#### Step 3: Copy the URL for the repository by hitting the copy button or selecting the text under the HTTPS tab

![image](https://github.com/irm1005-itec1005-fall-2023/template-exercise-01/assets/9325038/f0ff7f9b-780b-4e7a-99e9-cfd988af7926)

#### Step 4: Open up VSCode and select the "Clone Git Repositry" option on the start screen

<img width="1024" alt="Screenshot 2023-08-17 at 11 21 43 AM" src="https://github.com/irm1005-itec1005-fall-2023/template-exercise-01/assets/9325038/f5560804-91e7-499e-b5f9-4d6ea8e7e8b9">

#### Step 5: Paste the URL for the repository that copied in step 3

<img width="1021" alt="Screenshot 2023-08-17 at 11 24 08 AM" src="https://github.com/irm1005-itec1005-fall-2023/template-exercise-01/assets/9325038/e5337048-1c97-467c-b5ff-6bf3531ef4c7">

#### Step 6: Hit `enter` and VSCode will complete the cloning process by asking you where you want to save your tutorial 01 files on your local machin and then saving the files locally

### Understanding Git and GitHub

Now that you have your tutorial 01 repository code on your local machine, it's time to add changes to your code, commit those changes, and push them back up to GitHub so the changes are saved in the cloud for everyone to see.

The following two links are great resources that help further explain how we add and commit code to our repositories.

- [Atlassian Git add tutorial](https://www.atlassian.com/git/tutorials/saving-changes)
- [Atlassian Git commit tutorial](https://www.atlassian.com/git/tutorials/saving-changes/git-commit)

### Committing and pushing your code

The following instructions illustrate how you can modify a file, create a commit to capture the changes, and then push up your code to the GitHub repository in the cloud.

#### Step 1: Modify the `index.html` file, save your changes, VSCode will uses colour to denote changes to the file.

<img width="1021" alt="Screenshot 2023-08-17 at 11 40 48 AM" src="https://github.com/irm1005-itec1005-fall-2023/template-exercise-01/assets/9325038/8c7f9fc6-0750-41b8-96b6-b73250a05ed0">

#### Step 2: Open the Source Control vertical tab give us the current state of our changes

<img width="1021" alt="Screenshot 2023-08-17 at 11 42 12 AM" src="https://github.com/irm1005-itec1005-fall-2023/template-exercise-01/assets/9325038/1ec02845-fb16-4660-8a3c-c20c73509d9d">

#### Step 3: Before we can create our commit, we have to add a commit message (In this example I put "Add Index Page") and hit `Commit`.

<img width="1021" alt="Screenshot 2023-08-17 at 11 42 12 AM" src="https://github.com/irm1005-itec1005-fall-2023/template-exercise-01/assets/9325038/45f39169-9211-4a80-b55d-37c6484bc11c">

#### Step 4: Once your changes are committed, you can push the changes to your tutorial 01 repository on GitHub by hitting the `Sync Changes` button.

<img width="1021" alt="Screenshot 2023-08-17 at 11 42 22 AM" src="https://github.com/irm1005-itec1005-fall-2023/template-exercise-01/assets/9325038/08faa436-e193-49e3-8d7d-378580b5eee4">

#### Step 5: VSCode will change the colour of the modified file to denote no pending code changes. You'll notice below `index.html` is back to white from green.

<img width="1021" alt="Screenshot 2023-08-17 at 11 42 59 AM" src="https://github.com/irm1005-itec1005-fall-2023/template-exercise-01/assets/9325038/70a021d8-d35a-41ab-b4c5-b5f930515f92">

#### Step 6: If you navigate back to your tutorial 01 repository on GitHub, you will notice that the files have been updated with your latest commit.

<img width="915" alt="Screenshot 2023-08-17 at 11 43 22 AM" src="https://github.com/irm1005-itec1005-fall-2023/template-exercise-01/assets/9325038/3743a528-52e1-4d62-a48d-3e08076943e9">

### Activating GitHub pages

The last thing we need to do for tutorial 01 is to activate the GitHub Pages services so that GitHub starts a web server for us to serve our home page to the public.

#### Step 1: Go to the settings tab in your repository

<img width="1609" alt="Screenshot 2023-08-17 at 11 57 01 AM" src="https://github.com/irm1005-itec1005-fall-2023/template-exercise-01/assets/9325038/f0326d33-51ae-484d-ac1e-af9528162829">

#### Step 2: Select Pages in the left navigation

<img width="1609" alt="Screenshot 2023-08-17 at 11 57 10 AM" src="https://github.com/irm1005-itec1005-fall-2023/template-exercise-01/assets/9325038/fdfe9235-f072-4fbf-8237-0f65526c9f87">

#### Step 3: Select the Branch drop down (default set to None)

<img width="1620" alt="Screenshot 2023-08-17 at 11 58 42 AM" src="https://github.com/irm1005-itec1005-fall-2023/template-exercise-01/assets/9325038/164a2a4e-9b65-4c32-a59f-fe4e23dd4c6c">

#### Step 4: Change the branch being published to Main

<img width="890" alt="Screenshot 2023-08-17 at 11 59 16 AM" src="https://github.com/irm1005-itec1005-fall-2023/template-exercise-01/assets/9325038/9fc6eba9-e929-4ded-bbb6-24f7dfd08dcc">

#### Step 5: Hit the Save button

<img width="890" alt="Screenshot 2023-08-17 at 11 59 28 AM" src="https://github.com/irm1005-itec1005-fall-2023/template-exercise-01/assets/9325038/144611e0-dda0-4f67-aba3-ad74bb0a0e8b">

#### Step 6: When your site is deployed the address will be available (this may take a few minutes)

<img width="1614" alt="Screenshot 2023-08-17 at 12 02 59 PM" src="https://github.com/irm1005-itec1005-fall-2023/template-exercise-01/assets/9325038/c9889b06-a839-4d72-ab20-4004e0a774e4">

#### Step 7: Copy your link and post a comment in the show and tell discussion thread

[Tutorial 01 - Show and Tell](https://github.com/orgs/irm1005-itec1005-fall-2023/discussions/2)

#### Step 8: Congratulations! You are done.

## :octocat: Git and GitHub

Git is a **distributed Version Control System (VCS)**, which means it is a useful tool for easily tracking changes to your code, collaborating, and sharing. With Git you can track the changes you make to your project so you always have a record of what you’ve worked on and can easily revert back to an older version if need be. It also makes working with others easier—groups of people can work together on the same project and merge their changes into one final source!

GitHub is a way to use the same power of Git all online with an easy-to-use interface. It’s used across the software world and beyond to collaborate and maintain the history of projects.

GitHub is home to some of the most advanced technologies in the world. Whether you're visualizing data or building a new game, there's a whole community and set of tools on GitHub that can get you to the next step. This course starts with the basics of GitHub, but we'll dig into the rest later.

## :octocat: Understanding the GitHub Flow

The GitHub flow is a lightweight workflow that allows you to experiment and collaborate on your projects easily, without the risk of losing your previous work.

### Repositories

A repository is where your project work happens--think of it as your project folder. It contains all of your project’s files and revision history. You can work within a repository alone or invite others to collaborate with you on those files.

### Cloning

When a repository is created with GitHub, it’s stored remotely in the ☁️. You can clone a repository to create a local copy on your computer and then use Git to sync the two. This makes it easier to fix issues, add or remove files, and push larger commits. You can also use the editing tool of your choice as opposed to the GitHub UI. Cloning a repository also pulls down all the repository data that GitHub has at that point in time, including all versions of every file and folder for the project! This can be helpful if you experiment with your project and then realize you liked a previous version more.
To learn more about cloning, read ["Cloning a Repository"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).

### Committing and pushing

**Committing** and **pushing** are how you can add the changes you made on your local machine to the remote repository in GitHub. That way your instructor and/or teammates can see your latest work when you’re ready to share it. You can make a commit when you have made changes to your project that you want to “checkpoint.” You can also add a helpful **commit message** to remind yourself or your teammates what work you did (e.g. “Added a README with information about our project”).

Once you have a commit or multiple commits that you’re ready to add to your repository, you can use the push command to add those changes to your remote repository. Committing and pushing may feel new at first, but we promise you’ll get used to it 🙂

## 📚 Helpful links

### HTML

- [Intro to HTML - Prof3ssorSt3v3](https://www.youtube.com/watch?v=KUmuiqV1xME&list=PLyuRouwmQCjncCz8JChyPNRBvm2ONGYa2)
- [HTML Tutorial - MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML)
- [HTML Lists - MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)

### GitHub

- [A short video explaining what GitHub is](https://www.youtube.com/watch?v=w3jLJU7DT5E&feature=youtu.be)
- [Git and GitHub learning resources](https://docs.github.com/en/github/getting-started-with-github/git-and-github-learning-resources)
- [Understanding the GitHub flow](https://guides.github.com/introduction/flow/)
- [How to use GitHub branches](https://www.youtube.com/watch?v=H5GJfcp3p4Q&feature=youtu.be)
- [GitHub's Learning Lab](https://lab.github.com/)
- [Education community forum](https://education.github.community/)
- [GitHub community forum](https://github.community/)

### Git

- [Interactive Git training materials](https://githubtraining.github.io/training-manual/#/01_getting_ready_for_class)
