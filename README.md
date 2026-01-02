# Python Hello World (Future Connect)

## Summary

This is a simple hello-world project for Python that I added because I needed to prove to a certification trainer that I could initialize a GIT project and push it to GitHub.

## Things I did prior to creating this project

I ran all this on a brand new system that I recently setup with Ubuntu LTS. So I did the usual initial GIT setup stuff which includes:
1. Ensuring I have the latest GIT version (via PPA on ubuntu)
2. Setting up SSH on my system with the latest libs and agent
3. Adding a new ed25519 key for GH to use and registering it with my SSH agent then added it to my GH account.
4. Installing GH CLI and authorizing it (via SSH)
5. Configuring GIT (name, email, line feeds, default branch name, plus various other preferences)
6. Added a global ignore file for GIT to read from in my home ~/.git folder.

## How I created this project
1. Created a new folder for projects I will add for this particular organization
2. Created this project folder
3. Ran the following shell commands from inside the project folder:
git init
touch README.md & chmod 644 README.md
subl ./README.md (then edited the contents)
git add README.md
