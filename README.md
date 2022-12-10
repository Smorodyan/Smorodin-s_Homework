# GitHub instruction

## Commands:
	1. Check Git in MS Visual Studio: connect folder -> open Terminal -> git --version
	2. git init - git initiation
	3. Git status
	4. Git add [. - adding of all extensions; * - adds all files] <folder name>
	5. Git commit -m "comment"  
	6. Git log  - checking versions
	7. Git checkout <version/log number>
	8. Git checkout master - return to the main branch
	9. Git diff  - to see changes
	10. Clear - to wipe strings

## Four steps:
	1. Make changes in a file
	2. Save: Ctrl + S
	3. Add files for tracking: git add .\file name
	4. Commit: git commit -m "comment for changes"
	
	
## Branches:
	1. Create a new branch: git branch <name>
	2. See branches: git branch
	3. Move to a branch: git checkout <branch name>
	4. Move to master branch: git checkout master
	5. Delete branch: git branch -d <branch name>
	6. Tree view: git log --graph
	
	
## Branch merging:
	1. Move to master: git checkout master
	2. Merging: git merge <branch name>


## GitHub:
	1. Copy repository from GitHub in the Terminal: git clone <URL>
	2. After coping/cloning move to this folder: cd <cloned folder name>


## Fork from GitHub:
	1. Click "Fork" button on GitHub
	2. Copy repository from GitHub in the Terminal: git clone <URL>
	3. After coping/cloning move to this folder: cd <cloned folder name>
	4. Create a new branch, make changes and save
	5. Specify the new branch as a main branch and push it to GitHub: git push --set-upstream origin <branch name>
	6. On GitHub click "Compare & pull request"
	

## Upload to GitHub:
	1. Upload repository to GitHub: click + and create New repository on GitHub
	2. Specify remote repository: git remote add origin https://github.com/…
	3. Specify the main branch: git branch -M main
	4. Upload files: git push -u origin main
	5. Download updates from GitHub: git pull


	
## Git marks:
	U - untracked
	M - modified