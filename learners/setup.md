---
title: Setup
---

FIXME: Setup instructions live in this document. Please specify the tools and
the data sets the Learner needs to have installed.

# Data Sets

<!--
FIXME: place any data you want learners to use in `episodes/data` and then use
       a relative link ( [data zip file](data/lesson-data.zip) ) to provide a
       link to it, replacing the example.com link.
-->
Download the [data zip file](https://example.com/FIXME) and unzip it to your Desktop

# Software Setup

::::::::::::::::::::::::::::::::::::::: discussion

## Details

Setup for different systems can be presented in dropdown menus via a `spoiler`
tag. They will join to this discussion block, so you can give a general overview
of the software used in this lesson here and fill out the individual operating
systems (and potentially add more, e.g. online setup) in the solutions blocks.

:::::::::::::::::::::::::::::::::::::::::::::::::::

:::::::::::::::: spoiler

## Windows

Use PuTTY


## MacOS

Use Terminal.app

Please work through the sections in order. At the end of each part are instructions to test that stage of your installation.

### Homebrew - a unix package manager

[Homebrew](https://brew.sh) is a [package manager]() for useful tools, particularly unix command line tools which are not available on MacOS via the app store. It can be installed by opening a Terminal app install(from the Utilities folder inside the Applications tab) and then typing the commands below.
![]()

```bash
sudo echo "hello"
echo |/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

```

You will be asked to enter your password after the first command. Homebrew will install after the second.


You may be asked to access the Terminal on other occasions during the course, so it's work spending a second or two to remember where it lives. You can also secondary click (using two fingers, or the Option key) on the icon in the dock and select `Options > Keep in Dock` from the menu bar so that it is always readily available. 

When Homebrew finishes installing it recommends you run two commands to activate it, and to ensure it's automatically available whenever you open a Terminal window.

```bash
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> $HOME/.zprofile
eval "$(/opt/homebrew/bin/brew shellenv)"

```

Now that `brew` is installed and set up, we can use it to install some useful packages. From next week you'll be using `git` extensively so lets first install that.

```bash
brew install git
```
To ensure we can smoothly interact with `GitHub` lets configure our user name and email address
```
git config --global user.name "Your Name"
git config --global user.email "youremail@domain.com"
```
where `Your Name` and `youremail@domain.com` should be replaced with your `GitHub` username and associated email address respectively.

Lets next install [Miniconda](https://docs.conda.io/en/latest/miniconda.html). (We'll learn more about this package next week).
```bash
brew install miniconda
```
Next we need to update `conda`
```
conda update conda
conda update --all
```
Then run
```
conda init zsh
```
and restart the terminal.

We'll now use Miniconda to create the `ese-msc` environment. You'll make use of this environment during next week's lectures. Note that for the time being, you can simply
follow the instructions below and ensure that each step completes without error (i.e. there's no need to understand exactly what is going on) - you'll learn more
about Python environments during next week's lectures.

To start, let's use `git` to clone the repository containing the material for next week's lectures. Navigate to/create a folder where you want to store the lecture material.
When in the desired location ACSE students should run:
```
git clone https://github.com/ese-msc-2023/modern-programming-methods.git
```
EDSML and GEMS students:
```
git clone https://github.com/ese-msc-2023/numerical-programming-in-python.git
```
Note that when prompted to enter your username and password, the password is **not** your GitHub account password but a 'personal access token' created with suitable permissions. Instructions for creating a personal access token can be found [here](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token).

This repository contains an `environment.yml` file for building the `conda` environment. Navigate into the repository (e.g. `cd modern-programming-methods`). ACSE students should then run
```
conda env create -f environment.yml
conda activate ese-msc
```
ESML and GEMS students should run
```
conda env create -f environment.yml
conda activate npp
```
You should now see the environment name displayed on the left hand side of the terminal, e.g.

![](images/mac/mac_term.png)

Note that to deactivate an environment you can run
```
conda deactivate
```

### Visual Studio Code

Visual Studio code is a lightweight text editor with multiple features which make it suitable for inspecting & editing code. VS code offers a range of Microsoft & third-party extensions to support additional functionality. It can be installed via

```bash
brew install --cask visual-studio-code
```

Next, we will install a selection of add-ons to improve the experience when coding with Python

```bash
code --install-extension ms-python.python
code --install-extension ms-vscode.cpptools 
code --install-extension ms-vscode-remote.vscode-remote-extensionpack
code --install-extension ms-vsliveshare.vsliveshare-pack
```

## Linux

Use Terminal

::::::::::::::::::::::::

