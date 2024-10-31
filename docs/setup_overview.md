---
title: Pre-workshop setup
nav_title: Setup
---

Please complete all setup tasks __prior__ to the workshop, as we will not have time to go through installation steps and complete all goals of the workshop. 

If you need any assistance with the installation, please contact Ryan Corbett (corbettr@chop.edu)<br><br>


## Workshop software requirements

___

### Visual Studio Code

We will be writing code using [Visual Studio Code](https://code.visualstudio.com) text editor during the workshop, so we recommend downloading this if you do not have a preferred text editor. 
Alternatively, other text editors can be used such as [VSCodium](https://vscodium.com), [Sublime](https://www.sublimetext.com), or [BBEdit](https://www.barebones.com/products/bbedit/). 

### Command line tools (Mac users ONLY)

Mac users will need to install `md5sum` in order to download data sets from AWS S3 via an executable shell script. 
This can be done with [homebrew](https://brew.sh/) using the command `brew install coreutils`, or [conda/miniconda](https://docs.conda.io/projects/conda/en/latest/) using the command `conda install -c conda-forge coreutils`.

### Xcode (Mac users ONLY) 

Mac users will also need to install [Xcode](https://developer.apple.com/xcode/), if not already installed. 
You can check if Xcode is installed on your computer by running the following command:

`xcode-select -p`

If Xcode is installed, then a directory path showing it's installation location will be printed; otherwise, follow the link above to download to your computer. <br><br>


## Account Setup

___

### Github

You will need to create a [GitHub.com](https://github.com) account if you do not already have one. See [here](https://docs.github.com/en/get-started/onboarding/getting-started-with-your-github-account) for detailed account setup instructions. 


### Docker

We will be using Docker to showcase software and package tracking within Github repositories. Please download [Docker Desktop](https://www.docker.com/products/docker-desktop/) prior to the workshop. 

