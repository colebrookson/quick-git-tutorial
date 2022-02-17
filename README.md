# Git/GitHub Crash Course for Biologists

This is a quick tutorial I have written for my colleagues in the biological sciences. This tutorial, given live, can be completed in ~1hr if all participants have done the required prep work. The goal of this is not to teach the theory behind version control, nor to delve deeply into the details of `git`/GitHub, but to give you a digestible introduction to how to implement repositories into your workflow. 

**Required Background:** This workshop technically does not need any previous experience with `git` or GitHub, but will be most useful if you are a bit familiar with both. 

## Pre-Workshop Prep 

To get set up for this live session you will need a few key items: 

1. A GitHub account with an SSH key set up for the computer you will be using for this tutorial 

* Sign up for a [GitHub account here](https://github.com/join). It will only take a few minutes!
* Add an SSH key for your account
  * First [check for an existing key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/checking-for-existing-ssh-keys) 
  * If you don't have one, [generate an ssh key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) according to the instructions specific to your operating system 
  * You will then need to [add the ssh key to your GitHub account](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)
  * You can [test the connection](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/testing-your-ssh-connection) to make sure it works before continuing 
  
2. A way to interact with `git` via the command line. This can be done in a few ways<sup>1</sup>:

* If you are a Mac user, you can use the `Terminal` app which will be already installed in your computer
  * This will still require `git` to be installed through [one of these options](https://git-scm.com/download/mac) (I recommend the `homebrew` option)
* If you are a PC user, I recommend [installing Git Bash](https://git-scm.com/)
* In Linux just use the `Terminal`

3. A reasonably fast internet connection 

## How to use the tools

Okay, now that we're set up, let's talk a bit about the tools we're actually using before we go any further. Here is a quick presentation on version control, and Git/GitHub, that will appropriately set the scene. 

## Let's get our hands dirty 

With this knowledge of the theory under our belts, let's dive in. Start by opening up a browser, and navigating to your GitHub account. Also, open up a terminal, and navigate to the location you want to host this repository in. I personally recommend having a "github" folder in the root of your file system, for ease of use and access. 

```
cd ~/github
```

### Make a new repo

Let's first make a new repository: 

![bg](./figs/new-repo.png)


## Notes

1. You'll notice here I don't recommend using `git` through RStudio or any GUI (graphical user interface) options such as GitHub Desktop. While those are valid options, I do not think they are optimal for learning git nor for actually using it. I will speak briefly further on this during the session. You can still use a GUI option or one other than the options above if you would like, but I cannot guarantee the process will transfer well between the programs during the live session. 
