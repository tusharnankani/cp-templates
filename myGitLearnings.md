# myGitTerminology
This is a README.md file.                 
.md is markdown. 

README.md is used to generate the overview/summary you see at the bottom of projects. 

Github has their own flavor of Markdown. 
Order of Preference: 
    If you have two files named README and README.md, 
    the file named README.md is preferred,
    and it will be used to generate github's html summary.

# The Best way to Learn is, by Doing it.
#### TO MASTER MARKDOWN TEXT FORMATTING:

https://guides.github.com/features/mastering-markdown/

* mkdir *dir-name*
* git clone *website-of-the-repo*
* git status

* git add *file-name*
* git add -A
* git commit -m *"message here..."*
* git push origin master

* git diff *file-name*
* git checkout *file-name*

* git log

**A cool git command for you.
In your project, run this command to see a really nice log.**

* git log --topo-order --all --graph --date=local --pretty=format:'%C(green)%h%C(reset) %><(55,trunc)%s%C(red)%d%C(reset) %C(blue)[%an]%C(reset) %C(yellow)%ad%C(reset)%n'

I've been using this really cool git command for a long time called **git lg**. It's like **git log** but wayyyyyyyy better.


* git config --global user.email "example@email.com"
* git config --global user.name "Your name"


*that's it for now!*
