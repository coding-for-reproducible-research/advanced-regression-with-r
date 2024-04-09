---
layout: info_page
title: Installation instructions
---

# Pre Workshop Instructions

This workshop has a number of prerequisites:

1. R and Rstudio will need to be installed prior to the start of the workshop details for how to do with are included here.
2. Learners are expected to already be familiar with the basics of R, such as how to load a dataset from a local file and manipulate variables. For example you should be comfortable with all the material in our [Intro to R workshop](https://coding-for-reproducible-research.github.io/intro-to-r/).
3. There are 3 R packages that need to be installed in advance, code for this is included below. 

# Installation

Because R and RStudio work together, you need to install them both. The steps in this section should guide you through the process. Once installed, you will be working with RStudio and R will be running in the background. 

## How to Install R?

Installing R in 4 easy steps

<br>

**Step 1.** 

a. Go to: https://www.r-project.org/

b. Click on **CRAN** or **download R**.

<br>

*Note:* You'll only do this once, although, eventually you'll have to update to the most recent version. Follow the same procedure as today.


<br>

**Step 2.** Select a mirror

A *Mirror* is a server somewhere in the world with a copy of the program. Choose the mirror closest to you. For example, if you are in the UK, you can select the one from University of Bristol. Don't worry too much about this.

<br>

**Step 3.** Select the download appropriate for your computer (Microsoft, Mac or Linux)

<br>

**Step 4.** Open the program you downloaded and follow the instructions

*Note* - There is another tutorial identical to this one that shows the process you need to follow if you have a mac.

<br><br>

![Alt Text](images/gif_windows.gif)


## How to Install RStudio?

Yes, you need to install both R and RStudio. Follow this 3 easy steps:

<br>

**Step 1.** 
a. Go to: https://www.rstudio.com/products/rstudio/download/

b. Click on the free version **Download** button

<br>

**Step 2.** Select your download accordingly. 

<br>

**Step 3.** Click on the download and follow the installation instructions


<br>

# Install necessary R packages

There are three packages need for this workshop. The first two (devtools & learnr) are available from CRAN. The third is a package we have developed with the course materials in and is available from GitHub (cfrrRTutorials). 

This code will install these three packages.

```
install.packages("devtools") 
install.packages("learnr") 
library(devtools)
devtools::install_github("ejh243/cfrr-r-tutorials")
```

If you encounter any difficulties with installation please contact 
