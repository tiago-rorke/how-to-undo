# HOW TO UNDO - Intro to Git and GitHub for Non-Coders

_How to use these essential free tools to manage projects, share content, and collaborate, all while keeping a record of versions and changes made along the way._

---

Git is a free and open-source version control tool that widely used for working with code, and one of the essential tools enabling open-source collaboration.

While built for programmers, Git is an amazing tool that anybody can use to manage any kind of content.  Be it text, spreadsheets, images, vector drawings, or 3D models, you can put pretty much anything you want into a Git repository. Doing so will, almost like magic, allow you to easily manage versions of files, share and collaborate on them with your colleagues, create backups, and more.

Using Git you can, for example:
- Publish project documentation
- Manage versions of graphic design work such as posters or fliers
- Make a repository of assets such as logos or icons
- Organise, backup and synchronise your notes across different devices
- Create a Wiki for your community

Whilst simple to use, Git can be confusing for new users, especially for those who are not necessarily interested in using it for software development, as most tutorials and reference material is designed for learning to use Git with code.

In this hands-on workshop, you will learn all you need to know to start using Git to organise your projects, and to publish and collaborate on them using GitHub.

Whilst this workshop is aimed at people with no programming experience, coders are also welcome to participate :)

Topics covered:
- Installing and using Git, GitHub Desktop and Obsidian.
- Writing in Markdown
- Using Git locally
- Collaborating on a repository using GitHub
- Publishing a simple website using GitHub Pages

_The workshop will be in English._

---

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

- "Food to Fork" - add your own recipe to the repository to share
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


### Interesting uses of Git

https://github.com/solarpunklab/solarpunk-lab


---

## Notes

Working Directory verses Local Repository?
