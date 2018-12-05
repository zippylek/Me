download Git
https://www.git-scm.com
	Repository status of git
	1. Untracked
	2. Working Directory
	3. Staged		(Ready to be Commit in to Local Repository)
	4. Local Repository
	5. Remote Repository
<Check Version Git>
git --version

<Show config Git>
git config --global --list
git config --list

<Setup Config Git>
git config --global user.name "Firstname Lastname"
git config --gloval user.email "user@mail.com"
git config --list

=================================================================================
Local Repository
<Create Git Repository>
git init

<Show status files in Git>
git status

git add .
git commit -m "Descrition"

=================================================================================
Remote Repository
<Connect GitHub with Local Repository>
git remote add origin https://github.com/repositoryName.git
git push -u origin master

get fetch origin master

get pull origin master