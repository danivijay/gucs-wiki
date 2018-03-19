<img align="right" width="300" src="https://i.imgur.com/E4FlFju.png" alt="fork this repository" />

If you don't have git on your machine, [install it]( https://help.github.com/articles/set-up-git/).

## Fork this repository

Fork this repo by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

## Clone the repository

<img align="right" width="300" src="https://i.imgur.com/0JFVZuT.png?1" alt="clone this repository" />

Now clone this repo to your machine. Click on the clone button and then click the *copy to clipboard* icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```

where "url you just copied" (without the quote marks) is the url to this repository. See the previous steps to obtain the url.


<img align="right" width="300" src="https://i.imgur.com/mVX0aQO.png" alt="copy URL to clipboard" />

For example:
```
git clone https://github.com/this-is-you/gucs-wiki.git
```
where `this-is-you` is your GitHub username. Here you're copying the contents of the gucs-wiki repository in GitHub to your computer.

## Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd gucs-wiki
```
Now create a branch using the `git checkout` command:
```
git checkout -b <add-your-name>
```

For example:
```
git checkout -b add-alonzo-church
```
(The name of the branch does not need to have the word *add* in it, but it's a reasonable thing to include because the purpose of this branch is to add your name to a list.)

## Make necessary changes and commit those changes

After that open `README.md` file in a text editor. You must be familiar with Markdown, a lightweight markup language. Refer to this [cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) which gives information on how to use Markdown.

In this case, add your GitHub handle and Slack handle in appropriate place of `README.md:`, please note names are in alphabetical order of GitHub handle.

```
@guthub handle - slack handle(without @)
```

For example:

```
- @danivijay - Dani M Vijay
```


If you go to the project directory and execute the command `git status`, you'll see there are changes. Add those changes to the branch you just created using the `git add` command:

```
git add .
```

Now commit those changes using the `git commit` command:
```
git commit -m "<name-of-your-contribution>"
```
replacing `<name-of-your-contribution>` with your name of your contribution.

## Push changes to GitHub

Push your changes using the command `git push`:
```
git push origin <add-your-name>
```
replacing `<add-your-name>` with the name of the branch you created earlier.

## Submit your changes for review

If you go to your repository on GitHub, you'll see a  `Compare & pull request` button.  Click on that button.

<img style="float: right;" src="https://i.imgur.com/i9j9rgI.png" alt="create a pull request" />

Now submit the pull request.

<img style="float: right;" src="https://i.imgur.com/p71E6je.png" alt="submit pull request" />

Soon I'll be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.
