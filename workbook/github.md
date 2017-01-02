## GitHub Survival Guide

Here are some tips for getting your GitHub environment working correctly, and troubleshooting when things go wrong.

### Steps for creating a new repository

Git is kinda like Dropbox, but for code files. Git *repositories* are folders on your computer that have *magic powers*. These powers include:

* The ability to automatically synchronize files within the folder between your computer and GitHub.com
* Watching for changes you make to files, then giving you the ability to either move forward with those changes, or revert back
* Lots more, but those are the important ones...

In order to convert an ordinary folder on your computer into a magic one (i.e. turn it from a folder into a *repository*), follow these **one-time** steps:

1. Drag the folder from Explorer (Windows) or Finder (Mac) into the GitHub app.
2. When asked to create a repository, do it!
3. Type a commit message (something like "my first commit") and hit the *Commit* button.
4. Hit the "publish" button and follow the prompt on the window that appears. (Windows) If you don't see your GitHub username on this window, be sure to use the dropdown and select it.

Your mild-mannered, ordinary folder is now a REPOSITORY! There's no need to repeat these steps once it's done properly.

### Synchronizing changes

Once your repository is created, the GitHub app is always watching. If it detects that anything has changed in your repository folder, you'll see those changes in the GitHub app. To move those changes to GitHub.com (where everyone can see them), you'll want to commit-and-sync.

1. Type a commit message, describing the changes you made (for example, "added something awesome!") and hit the *Commit* button.
2. Hit the "sync" button.

You'll know everything went right if you see your changes at GitHub.com. Remember that your account at GitHub.com is public - if you can see it, I can see it... everyone can see it!

### Don't be that guy/gal

We will be creating a lot of code projects this quarter. You'll want to create a *new folder*, and subsequently, a *new repository* for each one of these projects. Your public website on GitHub is one of them. When we move on to creating new projects (e.g. team page, weather, poker, Buyflix, etc.), each one of these is a *new repository*. Tips for avoiding trouble:

**Don't put magic folders (repositories) inside other magic folders!!!** I cannot stress this enough. If your directory structure on your computer looks like this:

    Your Code Directory
    -- username.github.io
       -- website folder
       -- myteam
       -- weather
       -- poker

... you will be sad. When we create new applications in class, be sure to create a new folder that lives directly underneath your code directory, and create a new GitHub repository for each one of them. Like this:

    Your Code Directory
    -- username.github.io
    -- myteam
    -- weather
    -- poker

### I know you said not to ______, Brian, but I was surfing Facebook and did it anyway

At some point, you might have to hit the reset button.

1. Delete the username.github.io repository from Github.com and your Github app. 
2. Move the files you've been working on somewhere else on your computer. 
3. Create a new, empty folder called username.github.io in your code folder. 
4. Drag this new folder into your Github app. You'll be prompted to create a new repository. Do it!
5. Put your homework files *individually* into this new directory. Do not attempt to move the whole folder you've been working on, or things could get corrupted again.
6. Commit and publish.
