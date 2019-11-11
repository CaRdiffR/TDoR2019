# Data Explorer

## 1. Get set up

Open the [R Studio cloud instance](https://rstudio.cloud/project/590001) and 
take a look at the README.md to start exploring the data set.

If you want to work on your own laptop, you can install the latest version of 
the *tdor* package via

```
devtools::install_github("cardiffr/tdor", build_vignettes = TRUE)
```

Then start exploring

```{r}
library(tdor)
library(dplyr)
?tdor
vignette("exploring_data_set", package = "tdor")
```

## 2. Open/claim an issue

Issues related to the TDoR data are posted as issues on this repo: 
https://github.com/cardiffR/tdor2019/issues. We have added tags to indicate 
the type of task/difficulty/tools required - some don't even require R! 
Have a look through to find something you/your team would like to work on.

If you have a GitHub account, add a note to the issue thread to say you will 
work on it.  If you have your own idea, feel free to open an issue!

## 3. Share your work!

If you would like to share your work and have a GitHub account, you can 
upload it to the hackathon repo here: https://github.com/CaRdiffR/TDoR2019/upload/master
Choose "Create a new branch for this commit and start a pull request.".

### Advanced

If you would like more version control, you can fork the TDOR2019 repo. 

If you are working on RStudio.cloud

 - Go to https://github.com/CaRdiffR/tdor2019 and click on the Fork button.
 - On the forked repository that is created, click "Clone or download" and 
 copy the URL in the box (use https).
 - Back on RStudio cloud, move to the terminal tab and type 
 ```
 git clone https://github.com/YourUsername/TDoR2019.git
 ```
 to clone the repo, where the last part is the URL you copied.
 - Still in the terminal tab, specify your GitHub name and email
 ```
 git config user.name "Your Name"
 git config user.email "you@emailaddress.net"
 ```

If you are on your laptop
 
 - Go to https://github.com/CaRdiffR/tdor2019 and click on the Fork button.
 - On your fork on GitHub (https://github.com/YourUsername/tdor2019) click 
 "Clone or download" and copy the URL in the box (use https or ssh as you 
 prefer).
 - On your laptop open a new RStudio project from version control, selecting 
 the git option and pasting the URL in the dialog box.
 - If you do not have global identity settings for git on your laptop, 
 go to the Terminal tab and specify your GitHub name and email
 ```
 git config user.name "Your Name"
 git config user.email "you@emailaddress.net"
 ```

Use RStudio to create a branch to commit your changes. When the branch is 
ready to share, go to your fork on GitHub and click "Compare & pull request" 
to create the PR.
