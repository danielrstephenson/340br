# 340br

Course materials for CSE 340

# Changes From the Official Repo

This fork of the "official" repo from Blaine Robertson makes a few significant changes:

1. This version uses Git, GitHub and Docker.
2. Submitting a link to the private GitHub repo is part of the assignment. Each Activity is a commit, and each Enhancement is a commit.
3. All of the Objective 6 video requirements have been updated to require the Enhancement videos to include all of the points in the Grading Matrix. (This makes it easier for students to see if they have completed all of the requirements, and makes it easier to grade.)
4. All of the references to XAMPP have been changed to include the use of Docker. Docker is the primary method for creating a local development environment, but XAMPP is available if students already have that set up, or their computer hardware does not allow for Docker.

## Using Git and Docker

This course is well adapted to using Git and GitHub. Some of the main benefits for using Git and GitHub:

1. Students will be exposed to and required to use a version control system in the profession of software and web development. This gives them real world experience.
2. GitHub makes it easy for the instructor to see what changes were made with each Activity and Assignment.
3. The instructor can easily suggest changes (add comments) to a student's code and push to the student's repo. This gives added real world experience.

It is also very easy to set up Docker with containers for Apache, MySQL, and phpMyAdmin. An added benefit is that this setup can utilize a free domain "hack" to make the project look like it is being hosted from a real domain name. Both options are available; http://lvh.me and http://localhost.

Docker makes it easy to troubleshoot a students code in the exact same environment they are using. The student just sends a copy of their entire project directory, and the instructor can run the containers from the student project directory (after stopping their own running containers) and get a working copy of the student's project.

To Use Git, GitHub and Docker in the course, add to the Week 01 Activities the following:

## Added Activities

- [Installing Git](https://ammonshepherd.github.io/340br/phpmotors/views/git.html) (content management and version control)
- [Download and Install VS Code](https://ammonshepherd.github.io/340br/phpmotors/views/vscode-install.html) (including the extensions)
  - (06:35 mins, ["Install Visual Studio on Mac" Transcript](https://docs.google.com/document/d/e/2PACX-1vSwncKnss-b1Q_3YO77IAmXnrsktSqCiFzWiX2Wyp_xwDumvyX4MhRbuJZ1YWdqIykvJ5-u2y5aAVzc/pub) )
  - (02:43 mins, ["Install Visual Studio on Windows" Transcript](https://docs.google.com/document/d/e/2PACX-1vQrnhEFxe6K4HwD1YHwn7q7ZSrLkvefihkb8mWui17mRAL5vBSKcZGlW7ocytlNlBW5rKRihcHuchdr/pub))
- [Installing Docker](https://ammonshepherd.github.io/340br/phpmotors/views/docker-setup.html) (local development environment)
- [GitHub and VS Code](https://ammonshepherd.github.io/340br/phpmotors/views/github-vscode-setup.html) set up
- Download Common [VS Code keyboard shortcuts](https://ammonshepherd.github.io/340br/phpmotors/downloads/code-shortcuts.pdf)
- Stage and commit your changes to your local Git repository.
