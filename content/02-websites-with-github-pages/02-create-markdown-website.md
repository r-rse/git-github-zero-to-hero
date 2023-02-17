---
title: Create a Markdown Website
weight: 2
---

## Create a website landing page (`index.md`)

In GitKraken create a file in your repository called `index.md`. 

> `index` files have special meaning and represent the entry point to any website - the "Default" webpage.

To create a new file in GitKraken Client, we can **use the Command Palette**.

To initiate the Command Palette, hit <img src="/images/command-symbol.png" width="2px" style="align:left; display:inline; margin:0;"/> **| Ctrl + P**, type **Create File**, and hit Enter.

Then enter the file name `index.md`.

<img src="/images/web-1a-gk.png" alt="title picture" width="700px">


## Add content to `index.md`

I've added some welcoming text to my landing page.

I also added:

- a **hyperlink** to the workshop materials.
- an **image** which I sourced from [Unsplash](https://unsplash.com/photos/6wAGwpsXHE0) and **downloaded to the root of my repository**. I also added the attribution tag for the photographer who took the picture. This is actually in HTML but as you will see, markdown files can also render HTML content. 

<img src="/images/web-1b-gk.png" alt="title picture" width="700px">

```md
# My first Website

Welcome to my website! 

I created this website during [this workshop](https://r-rse-git-github-zero2hero.netlify.app/)

![](belinda-fewings-6wAGwpsXHE0-unsplash.jpg)

Photo by <a href="https://unsplash.com/@bel2000a?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Belinda Fewings</a> on <a href="https://unsplash.com/photos/6wAGwpsXHE0?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>


```

## Commit everything and push to GitHub

- Save any changes you made to `index.md`
- Stage `index.md` and any images you added.
- Commit.
- Push to GitHub.

<img src="/images/web-1c-gk.png" alt="title picture" width="700px">

## Enable the GitHub Pages

Now we need to **enable GitHub Pages** in order to tell GitHub to serve your repository as a website.

On your GitHub repository, go to the **<i class="fa fa-cog" aria-hidden="true"></i> Settings** (top right-ish tab).

<img src="/images/web-2a-gh.png" alt="title picture" width="700px">

In **Settings**, scroll down on the left navigation panel the **<i class="fa-solid fa-browser" aria-hidden="true"></i> Pages** section.

<img src="/images/web-2b-gh.png" alt="title picture" width="700px">

### Configure GitHub Pages

This opens up the **GitHub Pages panel** where we can configure how we want our website to be served.

<img src="/images/web-2c-gh.png" alt="title picture" width="700px">

Under the **Build and deployment** section:

- Leave the **Source** set tho **Deploy from a branch**.
- Under **Branch** choose the **`main`** branch and **<i class="fa fa-folder" aria-hidden="true"></i>
 `/(root)`** of the directory as the source for your website's content.
- Click **Save**.

Once you click on **Save**, GitHub will start building your website in the background (this might take a minute)

### Enable HTTPS

In the meantime, while our website is being built and in the interest of security, let's go ahead and **enable HTTPS** by scrolling down and ticking the **Enable HTTPS** option.

<img src="/images/web-2d-gh.png" alt="title picture" width="700px">


## View your website

Once your page is built, the details including the URL to your site will be shown on your GitHub Pages panel (you might need to refresh the page for it to appear).

<img src="/images/web-2e-gh.png" alt="title picture" width="700px">

Click on **Visit site** to launch your webpage!

<img src="/images/web-2f-gh.png" alt="title picture" width="700px">


### Add website URL to repository metadata

It's nice for visitors to your repository to be able to easily find their way to your website.

A simple way to do this is to add the URL to your website to your repository metadata.

To do so, first **copy the URL from your browser** (or your GitHub Pages panel).

Next, head back to the root of your repository on GitHub.

On the right hand **About** panel, click on the **<i class="fa fa-cog" aria-hidden="true"></i>** button.

<img src="/images/web-2g-gh.png" alt="title picture" width="700px">

Paste the URL to your site in the **Website** field and **Save changes**

<img src="/images/web-2h-gh.png" alt="title picture" width="700px">

Your now **easily get to your site through the About** metadata panel!

<img src="/images/web-2i-gh.png" alt="title picture" width="700px">

