# Introduction to git and github
Miguel Xochicale

# 

<div style="background-color: rgba(22,22,22,0.75); border-radius: 10px; text-align:center; padding: 0px; padding-left: 1.5em; padding-right: 1.5em; max-width: min-content; min-width: max-content; margin-left: auto; margin-right: auto; padding-top: 0.2em; padding-bottom: 0.2em; line-height: 1.5em!important;">

<span style="color:#939393; font-size:1.5em; font-weight: bold;">Introduction
to `git` and GitHub</span>  
<span style="color:#777777; font-size:1.2em; font-weight: bold;"></span>  
<span style="padding-bottom: 0.5rem;"><br> </span>  
[](http://mxochicale.github.io/) Miguel Xochicale, PhD  
<span class="dim-text" style="font-size:0.8em;">Zakaria Senousy,
PhD</span>  
<span style="font-size:0.8em;"><span style="border-bottom: 0.5px solid #00ccff;">[
`mxochicale/`](https://github.com/mxochicale/)</span>`{`<span style="border-bottom: 0.5px solid #00ccff;">[`intro-to-git-and-github`](https://github.com/mxochicale/intro-to-git-and-github)</span>`}`</span>

</div>

<div class="footer">

<span class="dim-text" style="&quot;text-align:left;'">2024-04-20 @
[Link for grid-worms-animation
2023](https://github.com/saforem2/grid-worms-animation/)</span>

</div>

# Overview

1.  [Automated Version Control](#markov)
    - [What is it? Why shoud I care?](#sec-issues-with-hmc)
2.  [Git and GitHub](#sec-l2hmc)
    - [commands: init, clone, status, pull, etc](#sec-su3)
    - [Workflow:issues, branches, PRs](#sec-su3)
3.  [References](#sec-references)
4.  [Exercises](#sec-extras)

## Automated Version Control

- **What is Automated Version Control?**
  - A system that automatically manages changes to files, typically in
    the context of software development.
  - Keeps track of every modification to the code in a special kind of
    database.
  - If a mistake is made, developers can turn back the clock and compare
    earlier versions of the code to help fix the mistake while
    minimising disruption to all team members.
- **Why Should You Care?**
  - **Backup and Restore**: Changes are stored securely and can be
    restored at any point.
  - **Collaboration**: Multiple people can work on the same project at
    the same time.
  - **Track Changes**: You can see who last modified something that
    might be causing a problem, who introduced an issue, when it was
    introduced, and more.
  - **Explore Alternatives**: Safely experiment with new ideas in a
    branch, without affecting the main project.

------------------------------------------------------------------------

## Introduction to Git and GitHub

- **Git**: A version control system that lets you manage and keep track
  of your source code history.
- **GitHub**: A cloud-based hosting service that lets you manage Git
  repositories.
- **Benefits**:
  - Track changes in your code across versions.
  - Collaborate with others on projects.
  - Backup your work on the cloud.

## Git command Basics

<div class="panel-tabset">

### Setting up

- **Installation**:
  - Download from [git-scm.com](https://git-scm.com/)
- **Configuration**:
  - Set your user name: `git config --global user.name "Your Name"`
  - Set your email:
    `git config --global user.email "your.email@example.com"`

------------------------------------------------------------------------

### Creating repo

- **Initialise a New Repo**:
  - `git init`
- **Cloning an Existing Repo**:
  - `git clone https://github.com/username/repository.git`

------------------------------------------------------------------------

</div>

## Git command Basics

<div class="panel-tabset">

### Making Changes and Committing

- **Track Changes**:
  - `git status`
  - `git add <file>`
- **Commit Changes**:
  - `git commit -m "Commit message"`

------------------------------------------------------------------------

## Pulling Updates

- **Using Git Pull**:
  - `git pull origin master`
  - This command pulls changes from the remote repository and merges
    them into your local branch.

------------------------------------------------------------------------

### Pushing Changes

- **Connect to Remote Repo**:
  - `git remote add origin https://github.com/username/repository.git`
- **Push Changes**:
  - `git push origin master`

------------------------------------------------------------------------

</div>

## GitHub workflow

:::

- Intro :wave:
- Workshop materials :arrow_down:
- Break :clock9:
- By the end of today :heavy_check_mark:
- Today’s plan :clipboard:

:::

## Hello :robot:

This presentation will show you examples of what you can do with Quarto
and [Reveal.js](https://revealjs.com), including:

- Presenting code and LaTeX equations
- Including computations in slide output
- Image, video, and iframe backgrounds
- Fancy transitions and animations
- Printing to PDF

…and much more

## Status of Large Language Models[^1]

![](https://github.com/Hannibal046/Awesome-LLM/raw/main/resources/image8.gif)

## Media Backgrounds

You can also use the following as a slide background:

- An image: `background-image`

- A video: `background-video`

- An iframe: `background-iframe`

<div class="footer">

Learn more: [Media
Backgrounds](https://quarto.org/docs/presentations/revealjs/#image-backgrounds)

</div>

## Absolute Position

Position images or other elements at precise locations

<img src="images/kitten-400-350.jpeg" class="absolute" data-top="170"
data-left="30" width="400" height="400" />

<img src="images/kitten-450-250.jpeg" class="absolute fragment"
data-top="150" data-right="80" width="450" />

<img src="images/kitten-300-200.jpeg" class="absolute fragment"
data-bottom="110" data-right="130" width="300" />

<div class="footer">

Learn more: [Absolute
Position](https://quarto.org/docs/presentations/revealjs/advanced.html#absolute-position)

</div>

## References

- [Version Control with
  Git](https://github-pages.ucl.ac.uk/git-novice/01-basics.html)

<div class="footer">

Learn more: [Quarto
Presentations](https://quarto.org/docs/presentations/revealjs/)

</div>

[^1]: [
    `saforem2/llm-lunch-talk`](https://github.com/Hannibal046/Awesome-LLM)
    [(slides)](https://saforem2.github.io/llm-lunch-talk)
