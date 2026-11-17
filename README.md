# UBIC Git Workshop Demo
Repository to practice Git skills in UCSD's UBIC Week 8 Workshop

## Setup Git Locally
First download Git from the official website using the following link: 
https://git-scm.com/install/
Choose Windows, macOS, or Linux depending on your operating system and follow the installation instructions.

Open your terminal and type the following.
```bash
git --version
```
You should see the version 2.56.1.

Create your git username and email. Replace "Your Name" with your actual name and "your-email@example.com" with your actual email. (*This is so that when you commit a change, you can be identified as the author of the commit. It is required by Git to have a username and email.*)
```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

To verify your Git configuration, type the following into your terminal. This should show your name, email, and default branch which should be set to "main".
```bash
git config --list
```

You now have Git installed locally and it's ready to be used!
