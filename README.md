# UBIC Git Workshop Demo
Repository to practice Git skills in UCSD's UBIC Week 8 Workshop

## Connecting your local work to a GitHub repository

If you haven't started working locally and would like to have access to an existing GitHub repository on your machine, you can clone it with the following command:
```
  git clone https://github.com/username/reponame.git
```
In order to get your repo link, you'll need to navigate to your repository home page, click on the green "Code" button, and copy the HTTPS link that appears.
After cloning, you can switch into the repository directory with `cd reponame`.


On the other hand, if you've already created a local repository with `git init` and would like to connect it to a remote repository created through GitHub, you can use the following command:
```
git remote add origin https://github.com/username/reponame.git
```
before using the following to send your changes to the remote repository:
```
git branch -M main
git push -u origin main
```
