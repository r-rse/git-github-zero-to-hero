---
title: Make changes to a file
weight: 6
---


We've created our `TODO.txt` file and committed it.

Let's go ahead and add some content to it.

Let's now add a to do list to our `TODO.txt` file

## Edit `TODO.txt`

To start editing our `TODO.txt`, right click on it in the right hand panel and click on

<img src="/images/work-6a-gk.png" alt="title picture" width="700px">	

This opens up the file again, **ready for editing.** 

**Add the following to do list:**

```txt
- Create first repository (done)
- Add a file to the repo (done)
- Modify file locally with to do list (done)
- Modify to do list on GitHub
 
```
This is what it looks like in GitKraken Client. Make sure you include an empty line at the end of the file. Also note the **blue dot indicates unsaved changes to the file**.

<img src="/images/work-6b-gk.png" alt="title picture" width="700px">

Next we need to **save the changes to our file** in the same way you would save any file on your system, with  <img src="/images/command-symbol.png" width="2px" style="align:left; display:inline; margin:0;"/> **| Ctrl + S**.

Git again detects the changes to the file and lists it in the **Unstaged Files**. This time however, it's preceded by an orange <i class="fa-solid fa-pencil"></i> pencil icon. That's because `TODO.txt` is not a new file. Instead, it is a file that git is already tracking but has now been modified.

<img src="/images/work-6c-gk.png" alt="title picture" width="700px">


Let's go ahead and stage our file and go through the process of commiting the changes

<br>

## Commit changes to `TODO.txt`

Next let's follow the same steps we did previously to commit our changes and synch our remote repository.

- Stage the `TODO.txt` file.
- Write an informative commit message.
- Make the commit.

<img src="/images/work-6d-gk.png" alt="title picture" width="700px">

- Review our commit history.
- Push the changes to our remote repository.

<img src="/images/work-6e-gk.png" alt="title picture" width="700px">