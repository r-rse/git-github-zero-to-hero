---
title: Add a file to the repo
weight: 4
---

Okay! Now we need to do something with the repository. Let's start with a basic use-case and make a single file where we will list some to-do items. The repository is just a normal folder on your computer where you can create and edit files like normal.


## Create new file

To create a new file in GitKraken Client, we can **use the Command Palette**.

To initiate the Command Palette, hit <img src="/images/command-symbol.png" width="2px" style="align:left; display:inline; margin:0;"/> **| Ctrl + P**, type **Create File**, and hit Enter. _You can also right click the empty space in the commit panel and click the Create File context menu option._

<img src="/images/work-1-gk.png" alt="title picture" width="700px">


Type the desired filename/filepath and hit Enter. Let's create a simple text file called `TODO.txt` in the root of our repository.

<img src="/images/work-2-gk.png" alt="title picture" width="700px">



You should now see the new file you added, opened for editing. It will also show up in the right hand panel. `git` has detected a new file in our repository which it’s not currently tracking. GitKraken Client let’s us know about it by listing it under the **Unstaged Files** with a green **+** indicating it’s a completely new file.

> __Unstaged Files:__ The unstaged files panel shows you an overview of all uncommited local changes to your repository since the last commit. You can also see the detailed changes to each file by just clicking on it. You have the option to **stage** all the changes or some of them. Staging is essentially a commit preparation process.

<img src="/images/work-3-gk.png" alt="title picture" width="700px">

<br>

## Commit `TODO.txt`

Now it's time to **commit** our file. This will effectively create a *save point* in our repository's history that we can come back to at any time. Aim to do this whenever you've done a small, complete chunk of work. 

GitKraken Client provides an easy to use interface for this job. First, click on **Stage File** in the file editing panel. Alternatively you could click on the **Stage all changes** button to stage all unstaged files in one go.

<img src="/images/work-4a-gk.png" alt="title picture" width="700px">

This moves the `TODO.txt` file to the **Staged Files** panel.

>  __Staged Files:__ Changes to files or folders which we select to be included in a commit are be moved to this area.

Next we wan't to add a concise yet descriptive commit message.

> __Commit Message:__ Commit messages are extremely important for identifying the contents of individual commits and make the difference in how much effort is required, by you or others, to identify a specific change, especially if a long time has passed since the change was made. well. An optional description filed allows you to add more detail on what was done and why.

<img src="/images/work-4b-gk.png" alt="title picture" width="700px">

Finally, we can commit our changes by clicking on **Commit changes to 1 file**.
    
> __Commit changes to n files:__ Pressing this button will commit our changes *to our local repository*.

A new commit now appears in our commit history:


<img src="/images/work-4c-gk.png" alt="title picture" width="700px">



<br>

## Push changes to remote

The commit we just made only exists in our local repository. Our remote repository is still one commit behind.

To synchronise our remote repository with our local one, we need to **push** our local changes up to the remote. 

We do this by clicking the **Push** button on the top of GitKraken Client navigation bar.

<img src="/images/work-5-gk.png" alt="title picture" width="700px">	

<br>

