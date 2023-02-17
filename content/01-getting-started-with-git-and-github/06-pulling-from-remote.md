---
title: Pulling from a remote repository
weight: 7
---
**Push** makes sure that your work is not only in your computer but "online" as well which means:

  - It is backed up.
  - You can access it from any location.
  - If your repository is open, other people can benefit from your work, they can contribute, reference you or even make recommendations.
  
Now, what if you you make changes directly on the GitHub repository or using another machine ? These changes are not locally synchronized with your primary computer. This is where **pull** comes into play.  

## Make a change on GitHub

### Go to GitHub repo

Navigate to your repository in GitHub and scroll down to *README.md*. GitHub automatically uses this file as a landing page to a repository which at the moment should be a mere *git-lesson*. 

### Open `README.md` for editing

To edit this file click on the small pencil icon on the top right hand corner. This icon is available for any file if you click on it but specifically for `README.md` it's also available as soon as you enter your repository.

<img src="/images/work-7a-gk.png" alt="title picture" width="700px">	


This will open up an editable version of the `README.md` file on GitHub that we can edit in the browser.

<img src="/images/work-7b-gk.png" alt="title picture" width="700px">	

### Edit `README.md`

Now let's **add some more details about the content's of our repo** to our README using *Markdown* text (more on markdown [later]({{< ref "/01-markdown-intro" >}}).

<img src="/images/work-7c-gk.png" alt="title picture" width="700px">

I added the following:

```md
# git-lesson

This repo was created as part of the Version Control for researchers workshop

**Location:** Online

```

When editing files on GitHub our issue, the main body of the editor contains two tabs:

- **<i class="fa fa-file-code" aria-hidden="true"></i> Edit:** where you make your edits.
- **<i class="fa fa-eye" aria-hidden="true"></i> Preview:** (if the content is markdown) where you can preview what the content will look like when it is rendered once the commit is made. 

Toggle the tabs below to explore this feature. Note how `#` and `***` notation is rendered in the Preview tab.

{{< tabs groupId="readme" >}}
{{% tab name="Edit" %}}
{{< figure src="/images/work-7c-gk.png" >}}
{{% /tab %}}
{{% tab name="Preview" %}}
{{< figure src="/images/work-7d-gk.png" >}}
{{% /tab %}}
{{% /tabs %}}

### Commit changes to `README.md`

Once you are happy with your changes, go ahead and **commit** them by clicking the **Commit changes** button.

<img src="/images/work-7e-gk.png" alt="title picture" width="700px">

This opens up a panel that should look somewhat familiar to you by now. Go ahead and **enter an informative commit message**. Also, leave the option to **Commit directly to the `main` branch** selected and click on **Commit changes**.

<img src="/images/work-7f-gk.png" alt="title picture" width="700px">

The changes to the `README.md` file have now been committed:

<img src="/images/work-7g-gk.png" alt="title picture" width="700px">

And are also now visible on the landing page of our repository:

<img src="/images/work-7h-gk.png" alt="title picture" width="700px">

## Pull remote changes to local repository

Now back in GitKraken Client, we see that our remote repository is ahead of our local one. 

<img src="/images/work-7i-gk.png" alt="title picture" width="700px">

In order to synchronize the local with the remote repository we can use **Pull**. This will "download" any updates from the remote repository to our local one.


<img src="/images/work-7j-gk.png" alt="title picture" width="700px">


Everything is now in synch again!

  