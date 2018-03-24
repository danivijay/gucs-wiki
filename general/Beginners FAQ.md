# Beginners FAQ

#### Qn : There is no **Chrome Canary** avalable for Linux platforms. What should I do?

Ans : All features described in the course is now part of standard Chrome itself.  Use standard **Chrome** ([download](https://www.google.com/chrome/)) or **Chrome beta** ([download](https://www.google.com/chrome/browser/beta.html)).

#### Qn : Where is **Resources** tab located in dev tools?

Ans : It is renamed as **Application** in newer versions of chrome.

![Application tab](https://imgur.com/mKKHzAm.png)

#### Qn : What are the pre-requisites to run the app used in course?

Ans : You should install **Node.js** [(download)](https://nodejs.org/en/) and **Git** [(download)](https://git-scm.com/) to get started.

#### Qn : Why do we need to run `git reset --hard` before working on every programming task? What does it mean?

Ans: `git reset` is a [git](https://git-scm.com/) command to revert any local changes to the application (wittr) you have made. This helps you work on the new task without any conflicts. the `--hard` flag means that git will not only erase the changes from the git repository but also revert them from your code so you will not be able to find it. Along with `git reset --hard` you will be required to run a command `git checkout <branch-name>`, here the `<branch-name>` signifies the task name which is nothing but another branch in the git repository having the starter code for that particular task.
