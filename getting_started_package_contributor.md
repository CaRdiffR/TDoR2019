# Package Contributor

## 1. Get set up

Open the [R Studio cloud instance](https://rstudio.cloud/project/590001) or 
RStudio on your laptop. Since you/your team plan to contribute to the package, 
you'll need to create a fork of the *tdor* package.

### If you are working on RStudio.cloud

 - Go to https://github.com/CaRdiffR/tdor and click on the Fork button.
 - On the forked repository that is created, click "Clone or download" and 
 copy the URL in the box (use https).
 - Back on RStudio.cloud, move to the terminal tab and type 
 ```
 git clone https://github.com/YourUsername/tdor.git
 ```
 to clone the repo, where the last part is the URL you copied.
 - Still in the terminal tab, specify your GitHub name and email
 ```
 git config user.name "Your Name"
 git config user.email "you@emailaddress.net"
 ```

### If you are on your laptop
 
 - Go to https://github.com/CaRdiffR/tdor and click on the Fork button.
 - On your fork on GitHub (https://github.com/YourUsername/tdor) click 
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

## 2. Open/claim an issue

Issues related to the tdor package are posted as issues on the tdor repo: 
https://github.com/cardiffR/tdor/issues. We have added tags to indicate 
the type of task/difficulty/tools required. Have a look through to find 
something you/your team would like to work on.

Add a note to the issue thread to say you will work on it. Feel free to open 
new issues if you spot something that needs fixing or have an idea for how to 
improve the package.

## 3. Do your work

Use RStudio to create a branch to commit your changes. 

## 4. Pull in other people's work

Hopefully the original *tdor* package will be updated during the hackathon. 
If this interacts with your work it's a good idea to sync every now and then 
with the Cardiff RUG repo. Bring your GitHub fork up-to-date by following 
[the easy way](https://twitter.com/revodavid/status/1187435324353302534).

## 5. Share your work

When your branch is ready to share, go to your fork on GitHub and click 
"Compare & pull request".
