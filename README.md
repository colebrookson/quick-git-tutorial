# Git/GitHub Crash Course for Biologists

This is a quick tutorial I have written for my colleagues in the biological sciences. This tutorial, given live, can be completed in ~1hr if all participants have done the required prep work. The goal of this is not to teach the theory behind version control, nor to delve deeply into the details of `git`/GitHub, but to give you a digestible introduction to how to implement repositories into your workflow. 

## Getting Started 

To get set up for this live session you will need a few key items: 

1. A GitHub account with an SSH key set up for the computer you will be using for this tutorial 

* Sign up for a [GitHub account here](https://github.com/join). It will only take a few minutes!
* Add an SSH key for your account
  * You will first need to [generate an ssh key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) according to the instructions specific to your operating system 
  * You will then need to [add the ssh key to your GitHub account](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)
  
2. A way to interact with `git` via the command line. This can be done in a few ways$^1$:

* If you are a Mac user, you can use the `Terminal` app which will be already installed in your computer
  * This will still require `git` to be installed through [one of these options](https://git-scm.com/download/mac) (I recommend the `homebrew` option)
* If you are a PC user, I recommend [installing Git Bash](https://git-scm.com/)





## Notes

1. You'll notice here I don't recommend using `git` through RStudio or any GUI (graphical user interface) options such as GitHub Desktop. While those are valid options, I do not think they are optimal for learning git nor for actually using it. I will speak briefly further on this during the session. You can still use a GUI option or one other than the options above if you would like, but I cannot guarantee the process will transfer well between the programs during the live session. 
