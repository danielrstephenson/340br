# GitHub and VS Code

This tutorial will guide you through connecting VS Code to your GitHub account.

## What is Git and why GitHub?

Git is a really smart content management tool, that also works well for version control. What is version control? It’s a way to keep track of the changes in your code. It’s like an undo for your whole project directory, not just your Word documents. See here for the theory behind Git: [https://docs.google.com/presentation/d/11nRaP3l_xwmZcJQZnYNkxLBJQ8TpIxejiZcfffvalx0/edit?usp=sharing](https://docs.google.com/presentation/d/11nRaP3l_xwmZcJQZnYNkxLBJQ8TpIxejiZcfffvalx0/edit?usp=sharing)

GitHub is an online service that hosts your git repositories. It provides a social aspect to your code. It is used by pretty much all software companies that host open source code. GitHub is not the only service out there, but it is the most well known. If you go further in the field of software or web development, you will most definitely interact with GitHub at some point.

## Create an account

The first step is to create an account at GitHub.com.

- Visit [https://github.com](https://github.com) in a browser.
- Click the Sign up button.
- Fill in the required fields for a unique username, email and password. You can uncheck the spam box – er, I mean Email preferences checkbox.
- Complete the “puzzle” by clicking the “Verify” button, then selecting the right images.
- Finally, click the big blue “Create account” button.

## Create a repo

The next step is to create a new repository. A repository is the folder that holds all your code. In our case, this is where we will put all our code for building the website during this course.

On the GitHub website, after you have logged in,

- Click on your profile icon on the top right of the page.
- Click the “Your repositories” link, then click the green “New” button.
  - Alternatively, if you are on the profile page already, click the “Repositories” tab, then click the green “New” button.
- On the New repository page, fill in a repository name. Something short and descriptive is best. No spaces or special characters. I would suggest phpmotors, php-motors, or cse340 as good options.
- Fill in a description if you like.
- Check the “Private” option. Leave the remaining checkboxes empty.
- Click the green “Create repository” button.

You are all done for now. Do not browse away from this page yet, as we will need a URL from this page later.

## GitHub and VS Code

Open VS Code. You should have done some initial setting up of VS Code already. The ability to use Git is built into VS Code. There is no plug-in or extension needed to use VS Code with Git or with GitHub.

If you already have a project open in VS Code, then go the “File” menu and select “New Window.”

- Notice the Git icon on the left sidebar. Click on that. ![Git icon in VS Code](assets/images/github-vscode/git-icon.png)
- You should see two pink colored buttons; one for “Open Folder” and one for “Clone Repository.” Click on the “Clone Repository” button. This opens the VS Code Command Prompt. ![Clone Repository button](assets/images/github-vscode/git-open-repo.png)
- Click on the dropdown option “Clone from GitHub”. ![Clone from GitHub button](assets/images/github-vscode/clone-from-github.png)
- A pop-up will ask if you want to allow the extension to sign in to GitHub. Click the “Allow” button. ![Clone Repository button](assets/images/github-vscode/allow-github.png)

Your browser will then open with a page asking you to continue authorization of VS Code to access GitHub.

- Click the big green “Continue” button. ![Click the big green button](assets/images/github-vscode/authorize-vscode.png)

You’ll see a success message with an alert box.

- Click the “Open Link” button. ![Open the link](assets/images/github-vscode/open-link.png)

This sends you back to VS Code with a prompt to allow the extension to open the URI (the address).

- Click “Open”. ![VS Code Open](assets/images/github-vscode/vscode-open.png)

After a second, you will see a drop down with all the repos in your GitHub account available.

- Pick the repo you just created. ![Pick your repo](assets/images/github-vscode/pick-repo.png)

- Next, VS Code will ask you to select a location on your computer to put the files. Pick anywhere on your computer. If you have a folder for this class already, you can select that folder. Note, this process will create a folder with the name of the repo, so select the parent folder where you want this repo folder to reside. ![Select a location to put your files](assets/images/github-vscode/select-location.png)

- Next click the “Open” or "Open in New Window" button on the VS Code notification pop-up. If the notification disappeared before you could click on it, you can click the little bell icon to get the notification to reappear. ![Open or Open in New Window](assets/images/github-vscode/open-in-vscode.png)

Now VS Code is connected to the GitHub repo and we can start adding files in VS Code.

## Git Workflow

Now is a good time to remind you of the workflow you will be using as you work through the assignments in this class.

Normally, when working with a version control software, you want to work on small discrete chunks of code. After each feature or chunk is complete, you submit that to the version control software as a commit.

For this course, you will break this pattern just a bit. Each week you have a Activity and an Assignment. You will submit one commit for all of the work you do in the Activity, and a separate, second commit for the Assignment (or Enhancement as they are called in this course).

So the process is, work on the Activity portion by making new files or editing the code in existing files by following the instructions in the Assignment section. Stage the work in Git. Then make a commit of the work in Git.

Next, work on the Assignment portion by making new files or editing the code of existing files following the Enhancement instructions. Then stage the work, and then commit the work.

Finally, you will push the commits from the local repository on your computer to the copy of the repository on GitHub.

We’ll walk through that process by adding a helpful file, called a README file that is used to explain what the repo is all about.

## The README file

Back in VS Code, make a new file by clicking on the new file icon, or go to the File menu and click “New File”.
![New file button](assets/images/github-vscode/readme-file.png)

We’ll use Markdown in this file, which is like a distant cousin to HTML. It makes text readable as plain text, but still has some syntax that allows computers to alter the display of the text, just like HTML.

In this new file type in:

```
  # CSE 340 – Winter 2021
  - Name: Your Name Here
  - email: yourname@email.com

  # PHPMotors
  - Learning how to build a website with PHP and MySQL.
```

Save the file and name it README.md. The `.md` is the file extension for Markdown files. GitHub will know what to do with it.

Now once you save the file, you should notice some things with Git icon on the left side menu. The Git icon now has a number, signifying that it now recognizes that one file has been changed.
![Git icon has changed](assets/images/github-vscode/git-icon-change.png)

If you click on the Git icon, a sidebar opens to display Git info. In this panel, you can stage the changes for a commit, add a message and commit the changes, and even push them to the GitHub repo.

- Stage the changes for a commit by pressing the plus icon.

![Git icons](assets/images/github-vscode/git-icons.png)

- To commit the changes, first type in a short message, then click the check mark or use the short-cut keys (command-Enter on Mac).

- Once you have committed the changes, you can push the changes to the GitHub repo. Click on the three-dots icon and select “Push”.

![Git push](assets/images/github-vscode/git-push.png)

If you go to the GitHub website in your browser and refresh the page, you should see the README.md file is now listed as a file, and the contents are displayed below.

To learn more about the Markdown language, see here: [https://guides.github.com/features/mastering-markdown/](https://guides.github.com/features/mastering-markdown/)

Note: If you discard the changes (the bent arrow icon), then all the changes you made to the file will be lost and the file will change back to how it was before you ‘staged’ it for the commit.
