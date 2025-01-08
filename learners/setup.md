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

When Homebrew finishes installing it recommends you run two commands to activate it, and to ensure it's automatically available whenever you open a Terminal window.

```bash
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> $HOME/.zprofile
eval "$(/opt/homebrew/bin/brew shellenv)"

```

Now that `brew` is installed and set up, we can use it to install some useful packages. From next week you'll be using `git` extensively so lets first install that.

**Git**
```bash
brew install git
```
To ensure we can smoothly interact with `GitHub` lets configure our user name and email address
```
git config --global user.name "Your Name"
git config --global user.email "youremail@domain.com"
```
where `Your Name` and `youremail@domain.com` should be replaced with your `GitHub` username and associated email address respectively.

**Miniconda**
Lets next install [Miniconda](https://docs.conda.io/en/latest/miniconda.html). (We'll learn more about this package next week).
```bash
brew install miniconda
```
**Conda**
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

