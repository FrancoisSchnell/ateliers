- 🤔 **Pour qui ?**
	- développeurs (programmation...) expl. [vlc](https://github.com/videolan/vlc)
	- chercheurs et [data journalistes](https://www.rue89strasbourg.com/la-surmortalite-en-alsace-pendant-la-periode-covid-vue-depuis-les-chiffres-de-linsee-177809) (programmes, jupyter notebooks...)
	- pour de la gestion de projet / "issues" ? ([github](https://github.com/features/issues), [gitlab](https://gitlab.com/gitlab-org/gitlab/-/issues))
	- autres ? ([supports du lab](https://github.com/FrancoisSchnell/ateliers), [cours python](https://git.unistra.fr/dbernhard/pythonm1s1), écrivains ?... )

- 🏛  **Histoire**
	- VCS (70s) : version control systems
	- contenu essentiellement **textuel**, **local** vs **distant** (dépôt, repository)
	- **Centralisé** (90s-00s) : cvs, **svn**...
	- **Décentralisé** (2005) : mercurial, **git**
		- Linus Torvalds (Linux, Git pour [gérer la complexité](https://www.process.st/how-was-linux-created/) des gros projets)
		- plus **complexe** (history et commit local, staging area, branches...) mais plus **puissant**
	  
- 📚 **Cas d'usages** 
	- **sans "comprendre" git** (github, gitlab)
		- aller sur un dépôt pour prendre un résultat (programme, notebook, zip...)
		- collaborer "socialement" à un projet: issues, wiki, requests 
		- éditer du contenu du dépôt directement depuis l'interface web
		- faire de la gestion de projet
	- **nécessite d'avoir git en local et de le "comprendre"**
		- cloner/publier un projet existant (le votre ou non) ou vous êtes membre du projet
		- faire une contribution occasionnelle ("pull request") pi vous n'êtes pas membre
	
- 🧰 **Outils**
	- 🕸 site web  distant : [github](https://github.com/), [gitlab](https://about.gitlab.com/) ([git.unistra.fr](https://git.unistra.fr/))
	- 📌 [git](https://git-scm.com/) (le cœur, outil en ligne de commande)
		- versions graphiques : [github desktop](https://github.com/apps/desktop), etc
	- 💾 vos logiciels de création de contenu ou code avec intégration de git 
		- [vscode](https://code.visualstudio.com/)
		- obsidian ([plugin git](https://github.com/Vinzent03/obsidian-git)), etc
	- 🔑 authentification
		- **https** (le plus simple pour vscode et github)
		- **clés ssh** (souvent pour les autres outils)
			- 📺 [tuto](https://www.youtube.com/watch?v=7K7xt0VJg5s)
			- 🔐 [créer un clé SSH](ssh-key.md)
		
- 💻 Git en ligne de commande
	- **git config** (user name, email, type de résolution de conflits; 
	  writes in .gitconfig file in your home)
		- git config --global user.name "YourUserName"          
		- git config --global user.email "your email"
		- git config --global pull.rebase false     (le plus simple pour les débutants)
	- git status
	- git init
	- **git pull** (toujours à faire au début d'une séance de travail)
	- git add
	- git commit
	- git push
	- git merge
	- git branch
	- ...

 - 🪟 Git dans vscode
	 - ouvrir un dossier/projet
	 - ouvrir "source control" (icone dans la barre d'outil à droite)



