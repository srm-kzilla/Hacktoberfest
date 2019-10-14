# Hack your way through October
![Author - SRMKZILLA](https://img.shields.io/badge/author-SRMKZILLA-orange)
![Open Source](https://img.shields.io/badge/-Open%20Source-green)
![Hacktoberfest](https://img.shields.io/badge/-Hacktoberfest-purple)

Brace yourself for a month of awesomeness and intense coding: it's  [Hacktoberfest](https://hacktoberfest.digitalocean.com/)!

Hacktoberfest is one of the biggest open-source fests of the year. You just have to submit 4 Pull Requests to any open-source repository, and you can get some cool swags from DigitalOcean!

If you don't know where to begin, don't fret. We at [SRMKZILLA](https://srmkzilla.net/) will guide you through your first open-source contribution.

Let's get cracking!
## Install Git
Git is the most widely used version control system in the industry today. Git allows you to keep track of all the changes you make to your project and go back a step (or many, your call) if anything goes south.

You can get started with Git by downloading it from [the official website](https://git-scm.com/downloads) and installing it.

To check if Git was installed properly on your system, go to the Command Line (Terminal on Linux based systems), type `git` and hit Enter. If a bunch of lines pop up telling you how to use Git, you are good to go. If it complains that it cannot find `git`, something went wrong. Hint: you probably need to add Git to your `PATH` environment variable.

![
](https://i.imgur.com/7Yjg88B.png "Check if Git was installed properly")
## Register on GitHub
GitHub is the de facto code sharing platform in the industry. It hosts your code for you so you can show off your awesome projects to the world. GitHub uses Git (hence the name) for version control.

![
](https://imgur.com/EmEjjqd "Register on Github")

To get started with GitHub, head over to [the website](https://github.com) and create an account. 
## Register for Hacktoberfest
To tap into the awesomeness that is Hacktoberfest, go to [their website](https://hacktoberfest.digitalocean.com/start) and register with your GitHub account. This is to keep track of all the contributions that you make.


## Fork our repository
To contribute to any repository on GitHub, you first need to **fork** it. Forking essentially means making a copy of a repository so that you can make changes to it without affecting the original version.

To make your first contribution, [fork our Hacktoberfest repository](https://github.com/srm-kzilla/Hacktoberfest). You will be able to see Hacktoberfest on your own repositories list after this step.

![
](https://i.imgur.com/Pqg7Ivt.png "Fork our repository")

## Clone the repository you just forked
Let's get to the fun part: actually messing around with the code. But before that, you must first download the code from GitHub. This is called **cloning** a repository.

To clone a repository, you need its URL. To get the URL of any repository, click on the green coloured button title "Clone or download", and copy the link you see.

Then go to your command line, and execute this command. Make sure you are in the directory you want to download the source code in.

`git clone url` 

Replace `url` with the link you copied. Wait for a few seconds, and then you should see the source folder downloaded to your directory.

![
](https://i.imgur.com/wGceXAR.png "Clone the repository")
## Add your name to `Contributors.md`
Open up the repository folder in your favourite text editor. If you don't have one, you can use [Visual Studio Code](https://code.visualstudio.com/download) (which is a hugely popular open-source project on GitHub). Anything but Notepad will do.

Open the file `Contributors.md`. You should see the list of people who have contributed to this project. Go ahead, add your name in there too. You deserve it.

![
](https://i.imgur.com/vQ4AC7N.png "Add your name to Contributors.md")

## Edit the HTML file
Next step is to add your name on our website. But this is not a one-line change. For this you need to edit the `index.html` file. The comments in that file will guide you through the editing part. You just have to copy the boilerplate section and edit it to add your name. 

![
](https://i.imgur.com/8XMhniH.png "Edit the HTML file")

You can open `index.html` in your browser to see the edited website.
## Commit your changes
Now that you have made all the changes required, you can tell Git to save these changes and **commit** them to its memory.

Before commiting the changes, you must tell Git which files are suppossed to be considered for the commit. This is called **adding** files. To add files execute the following command:
`git add file1 file2 ...`

In our case, the command would be:
`git add Contributors.md index.html`
 
 To check which files are yet to be added, you can run `git status`. This is a very handy command which tells you which files are not added, and which files are added but not committed yet.
 
 ![
](https://i.imgur.com/kYWImJG.png "Add the files")

 To commit the changes, execute the following command:
 `git commit -m "commit message"`
 Every commit must have a short message that describes the changes. This messasge is wrapped in double quotes in our `git commit` command.

You can run `git status` again to see that there is nothing new to be committed. This means that all your changes were recorded by Git.

![
](https://i.imgur.com/79ehN7D.png "Commit the changes")

## Push your changes

Before pushing your changes, you must first ensure that they were committed. Run `git status` to check this.

To push your code, execute the following command:
`git push origin master`

![
](https://i.imgur.com/FJ7VVM5.png "Push your changes")
## Create a Pull Request
The code you just pushed exists only in your version of the repository. To integrate the changes into the original Hacktoberfest repository, you need to create what's called a **Pull Request**. A Pull Request is essentially a request to the owners of a repository to add your code. This is what makes open-source projects so powerful, anyone can come and bring in their creativity.

If you go to your repository, you will see a bar on the top suggesting you to create a new Pull Request. Click on it. You will be taken to a screen which shows you all the changes you made, and a box in which you can add comments on the pull request. Note that this is different than the messasge you entered for a commit.

A pull request can have multiple commits. Anyone can come in and suggest edits to a pull requests to further refine the changes. Pull Requests really are what makes the open-source community so powerful.

![
](https://i.imgur.com/Gv3XakV.png "Pull Request")

![
](https://i.imgur.com/GQZc5sJ.png "Pull Request")

![
](https://i.imgur.com/clEUFfT.png "Pull Request")


Submit the Pull Request and we will review it as soon as we can.
## Voila!
Give yourself a pat on the back, because you have just taken the first step on your journey of open-source contributions. Welcome to the community!

We love pats, too. It would really be helpful to us if you would star this repository to let us know that you appreciate our endeavours.

If you got stuck somewhere or have any questions (or just wanna say hello), feel free to reach out to us at [technical@srmkzilla.net](mailto:technical@srmkzilla.net).

Happy Hacking!
## Next steps
You are now all set to conquer the world of open-source!
1. Explore around GitHub to find a lot more open-source repositories.
2. Submit a PR to the repository. A PR can be anything from a simple typo fix to an entire codebase rewrite.
3. After submitting a total of 4 PRs (including the one you submitted in this tutorial), you are now qualified to get some cool swags from DigitalOcean.
4. Head over to the [Hacktoberfest website](https://hacktoberfest.digitalocean.com/profile) and claim your swags!

## SRMKZILLA :hearts: Open-Source
> In the spirit of openness, for the love of open-source.

Open-source software is at the heart of SRMKZILLA. At SRMKZILLA, we’ve always used open-source to innovate. We want to give something back; we enjoy being a part of the community. We often release code or share best practices we developed. But sometimes, it's just fun and interesting code.

Do check our team out [here](https://srmkzilla.net/us.html)!

Wanna see what's cooking? [Here you go](https://github.com/srm-kzilla)!
