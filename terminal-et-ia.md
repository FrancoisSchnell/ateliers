- ⬛ **Terminal** (fenêtre entrées-sorties) vs **Shell** (interprétation des commandes) [vidéo](https://www.youtube.com/watch?v=8-ZIby5U7LU)

- 📚 Plusieurs **shells** du monde Unix : **Bash, Zsh**... du monde Windows : cmd, PowerShell...
- 💾 Installation
	- 🐧 Linux : ctrl + alt + t
	- 🍏 mac : command + space : terminal
	- 🪟 Windows : 
		- [Git Bash](https://git-scm.com/install/windows) : le plus simple à installer (cliquer sur "suivant" lors de l'installation) 
		- [WSL](https://learn.microsoft.com/fr-fr/windows/wsl/install) : plus complet mais un peu plus dur à installer (📺 [tuto](https://youtu.be/zZf4YH4WiZo?si=8HeqwM0CLRpiksxU))
		  
- 🤖 **Aide IA** 
	- dans le navigateur : [gemini](https://gemini.google.com/app), [chatgpt](https://chatgpt.com/), [mistral](https://chat.mistral.ai/chat), [grok](https://grok.com/)
	- dans le terminal : [ollama](https://ollama.com/) plus "agentique" : [gemini cli](https://geminicli.com/)
  
- 📰**TUI** (Textual User Interface) vs 🪟 **GUI** (Graphical User Interface)
	- GUI grand public : Macintosh (1984), Windows 3 PC (1990) 
	- serveurs, calculateurs, raspberry pi, ...
	- assistance IA ?
	- lancement d'applications ?
	- transparence des erreurs ?
	- automatisation ?
	  
- 🤔 Philosophie **UNIX**  
	-  📺 [UNIX: Making Computers Easier (1982)](https://www.youtube.com/watch?v=XvDZLjaCJuw)
	- Faire une **seule chose et la faire bien**
		- nom courts, richesse des paramètres
	- Tout est  un flux de **texte** et/ou **fichier** 
	- Encourage la **composition**
		- commande 1 | commande 2 | commande 3
		- Le Tuyau (pipe) **|**  (**windows** Azerty : AltGr + 6, **Mac** Option + Shift + L)
		- **>** (écraser) et **>>** (ajouter) vers un fichier.
		
- ⛵ Exercices
	- **droits** : **sudo** (super user do)
		- **mise à jour**
			- sudo apt update
			- sudo apt upgrade
			- sudo apt install vlc
	- **naviguer** : **ls,** cd, pwd
	- **lire** : cat, less  (cat text1.txt text2.text > text3.txt)
		- **transformer** : **sed** 's/chien/chat/g' test.txt
	- **créer** : mkdir, rm, mv, vim, nano
	- **tâches** : ps, grep, top, htop, btop...
	- **alias** et fonctions add to .bashrc (linux, windows) or  .zshrc
		- ls -lah
	- **fonctions** : [pdf shrink](https://x.com/i/grok/share/inU0pVkgUE3SYCyLzpRL8mESo)
	- **scripts ?** .sh
	- **ssh**
	- **[git](https://git-scm.com/)** ([gitlab](https://git.unistra.fr/), [github](https://github.com/))
		- [atelier git, github, gitlab](atelier-git-github-gitlab.md)
	
  