# HOW TO UNDO - Intro to Git and GitHub for Non-Coders

_How to use these essential free tools to manage projects, share content, and collaborate, all while keeping a record of versions and changes made along the way._


While built for programmers, Git is an 


---

Git is a free open-source version control tool



Whilst simple to use, Git can be confusing for new users, especially for those who are not necessarily interested in using it for software development.  In this 3 hour workshop, you will learn all you need to know to start using git to organising



## Outline

- [Introduction]
	- Workshop outline
	- Git, GitHub, Git terminology, Version Control, Background

- Install Git
	- https://github.com/git-guides/install-git
	- Check if it is already installed with `git version` in the terminal
	- MacOS - Install using Homebrew
	- Windows - Download and install Git for Windows

- Install GitHub Desktop, our "Git GUI Client"
	- https://desktop.github.com/
	- Temporarily set `name` and `email` to anything you like

- First Repo
	- Make a new repo with a README called `learning-git`.  Have a look at the folder this creates for you.
	- Open README.md in a text editor (Notepad, TextEdit, etc...), and give it a nicer title and summary sentence.
	- In GitHub Desktop, make a commit and see how this appears in the history tab.
	- Make a new file in the text editor, write a todo list and save this as `todo-list.md`.  Edit README and make a note of the to do list as well.
	- In the GitHub Desktop, make another commit and give it an appropriate summary message.
	- Add any other notes you'd like to the readme file, under a **Notes** section, or make a new file called `notes.md`

- [Summary]
	- Commit, README files
	- What is markdown?

- Install Obsidian
	- https://obsidian.md/download
	- Select `Open folder as vault` and select the `learning-git` folder.
	- Change the vault settings (see [obsidian setup](#Obsidian-Setup-for-GitHub-Compatibility))
	- Add an "install and use Obsidian" task to the to do list, and add check boxes to the tasks
	- Add a link to the todo list in the readme file

- Food to Fork - add your own recipe to the repository to share
	- https://github.com/tiago-rorke/food-to-fork/
	- clone the repository from GitHub (File > Clone Repository > URL)
	- Open as vault in Obsidian, and change the vault settings again. (Unfortunately this must be done each time you create or open a new vault).
	- Create a folder for your recipe, and put a new note in that folder.  Add any pictures you would like to include to that folder as well.
	- Once you are ready to publish the recipe, make sure you have committed all your changes, and have updated your local copy with `Fetch` and `Pull`.  If there are no conflits to resolve, you can publish with `Push`.

- [Summary]
	- Checkout, HEAD, branch, 


## Obsidian Setup for GitHub Compatibility

In `Settings`

 - `Files and Links` >
	- `New link format` - set to `Relative path to file`
	- disable `Use [[Wikilinks]]`
 - `Editor` >
 	- `Strict line breaks`



## Glossary

`repo`
`add`
`stage`
`commit`
`checkout`
`push`
`pull`
`fetch`
`branch`
`merge`
`diff`
`fork`
`clone`
`revert`
`rebase`
`stash`
`tag`
`origin`
`remote`


`version control` / `source control`

`distributed version control`


---

## Links

https://github.com/git-guides/install-git

https://github.blog/2015-06-08-how-to-undo-almost-anything-with-git/

[Dan Shiffman the Coding Train - Git and GitHub for Poets](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6ZF9C0YMKuns9sLDzK6zoiV)


---

## Notes

Working Directory verses Local Repository?
