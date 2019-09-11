# Setup a free Github Pages site for your Resume

A great way to share what you've done to recruiters is a website showing off what you know. This guide will explain how to make a SIMPLE webiste. Anything more complex, I'd recommonded looking elsewhere for hosting other than GitHub.

## What you'll need

- A Github account
- A domain
- An HTML page
- Patience

## Begin with Github

A GitHub account is free. Once an account is made, hit the `+` button on the top right of the screen and make a new repository

![Create Repo Button](https://guides.github.com/features/pages/create-new-repo-button.png)

When you make a reposity, make sure to name it your username dot github dot io. Since my username is `kylebaker` my repository will be named `kylebaker.github.io`.

![Crate Repository](https://guides.github.com/features/pages/create-new-repo-screen.png)

## Make an html page

For my use case, I'm choosing to use a very baisc HTML page for several reasons. One, a simple page is easy to load on a bad conneciton, which when sharing your website at conventions, generally have poor internet connections. Two, a basic html page doens't have to be updated for security issues. It shows just what you've designed and doesn't have any funcitonality that you don't need. 

A good template for those that don't know how to make a website is [one provided for free here](http://www.thomashardy.me.uk/free-responsive-html-css3-cv-template). You can download the CV template, unzip it, and edit the files in your editor of choice (I use [sublimetext](https://www.sublimetext.com/)). You can replace the `headshot.jpg` image with an actual image of yourself, just make sure to keep the name the same since it's referenced in the html code. The `style.css` file is how websites get their stylings, or colors and any special formating. You can mess with this file if you want to change the stylings of the defualt website. And finally, the meat of the 3 files, `index.html`. Here you will change almost everything to reflect you and your expereince. Once those 3 files are done, or if you decided to make one from scratch, you'll need to upload these files to the repository you made earlier. 

## Uploading to GitHub

There are multiple ways to upload files to GitHub, the easiest way for someone new to all this is using the [GitHub Desktop Client](https://desktop.github.com/), so I'll use that for this tutorial. 

Once the Desktop Client is installed and you are logged into your account, you'll want to "clone" the repository you made earlier to your local computer. In the client, go to `File` and click `Clone Repository` from the dropdown as shown below.

![Clone menu](https://help.github.com/assets/images/help/desktop/clone-file-menu-windows.png)

From there, you should see your repository titled `username/username.github.io`. For me, it'll be shown as `kylebaker/kylebaker.github.io`, select it and click "clone".

![Clone Repository](https://help.github.com/assets/images/help/desktop/clone-a-repository-list-win.png)

This will create a local instance of your repository on your local computer in `\Users\YourName\Documents\GitHub\`. Since I'm on Windows, I go to that location using the File Explorer. Once there you should see `username.github.io` folder, open that, and copy all files pertaining to you website here. 

Once done, when you go back to GitHub Desktop, you should see your "changes" here. 

![Changes](https://help.github.com/assets/images/help/desktop/getting-started-guide/viewing-changes.png)

Here you'll want to make a comment on what you did. This helps track what changes you make over time. 

![Comment](https://help.github.com/assets/images/help/desktop/getting-started-guide/commit-message.png)

And click the "Commit to Master" button.

![Commit](https://help.github.com/assets/images/help/desktop/getting-started-guide/click-commit-to-master.png)

Once you have committed the changes to your repository, you now need to "push" the changes to origin, origin being GitHub online. This will actually upload what you just did to GitHub. 

![Push](https://help.github.com/assets/images/help/desktop/getting-started-guide/push-to-origin.png)

## Testing your site

At this point, your website should be accessible to view in your browser as is. You'll want to type `http://username.github.io` replacing username with yours. If it works, the hardest part of this project is over. If it doesn't, either you'll need to wait for github to fully create your site, or an error occured and you'll need to adjust the files you just uploaded. 

## Creating a Domain for your Site