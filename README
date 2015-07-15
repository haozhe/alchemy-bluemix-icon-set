This is the repo to store all alchemy/bluemix specific icons (outside of IBM Design Language icons).

In order to use it, run the following command to install it as a bower package.

```
bower install git@git.design.ibm.com:alchemy/icon-set-alchemy-bluemix.git
```

## How to add new icons/ modify existing icons
If you have pulled down the project before, jump to 4.
1. Open Terminal/ Command Line Tool
2. Navigate to the location (e.g. Projects folder on Desktop) where you want to place files from this repo:
	
	```bash
	cd ~/Desktop/Projects/
	```
3. Pull down the repository with the following command:
	
	```bash
	git clone git@git.design.ibm.com:alchemy/icon-set-alchemy-bluemix.git
	```
4. Add icons to the svg folder, or modify existing icons. Notice that the icons should be named following this [naming convention](#naming-convention).
5. Bring up Terminal/ Command Line Tool and navigate into the folder for the repo (e.g. ~/Desktop/Projects/icons):
	
	```bash
	cd ~/Desktop/Projects/icons
	```
6. Check to see a list of added/modified icon files:
	
	```bash
	git status
	```
	
	You should be able to see outputs similiar to this:
	
	
	```bash
	On branch master
	Your branch is up-to-date with 'origin/master'.
	Untracked files:
	(use "git add <file>..." to include in what will be committed)

	svg/awesome-icon.svg
	svg/another-awesome-icon.svg
	svg/a-not-that-cool-icon.svg

	nothing added to commit but untracked files present (use "git add" to track)
	
	```
	
7. Add added/modified icons so that they are tracked:

	```bash
	git add -A
	```
'-A' will add all the modified files, alternatively you can also add icons individually by specifying their path and filename.
	
8. Check to see if changes to icons are tracked successfully:
	
	```bash
	git status
	```
	
	You should be able to see outputs similiar to the following:
	
	```bash
	On branch master
	Your branch is up-to-date with 'origin/master'.
	Changes to be committed:
  	(use "git reset HEAD <file>..." to unstage)

	new file:   svg/awesome-icon.svg
	new file:   svg/another-awesome-icon.svg
	new file:   svg/a-not-that-cool-icon.svg

	```
	
9. Commit new/modified icon files to your local repo:

	```
	git commit -m "This is some informative commit message."
	```
	
	Then you should see:
	
	```bash
	[master 0001f5f] This is some informative commit message.
 	3 files changed, 51 insertions(+)
 	create mode 100644 svg/awesome-icon.svg
 	create mode 100755 svg/another-awesome-icon.svg
 	create mode 100644 svg/a-not-that-cool-icon.svg
	```
	
10. Now that your icons are committed to your local repo, you are ready to push these shiny icons to the remote repo on github.ibm:

	```bash
	git push origin master
	```

11. Let Stan know that your icons are pushed, he will generate the svg sprite for these icons for developers to use.

## Naming Convention <a id="naming-convention"></a>

Each icon will have a css class, all icon class names start with the prefix '.bx-', followed by a descriptor of what the icon is, then optionally a modifier that starts with '_'.

Below is a list of valid icon class names:

* .bx-container-service
* .bx-vm-image_ibm
* .bx-vm-image_myorg

To make sure class names are generated correctly, you will need to name the icon files as such:

* container-service.svg
* vm-image_ibm.svg
* vm-image_myorg.svg