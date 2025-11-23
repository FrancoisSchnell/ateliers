
- 🤖 **Aide IA** 
	- dans le navigateur : [gemini](https://gemini.google.com/app), [chatgpt](https://chatgpt.com/), [mistral](https://chat.mistral.ai/chat), [grok](https://grok.com/)
	- dans le terminal : [ollama](https://ollama.com/) plus agantic : [gemini cli](https://geminicli.com/)
	
- ⬛ **Terminal** (fenêtre entrées-sorties) vs **Shell** (interprétation des commandes) [vidéo](https://www.youtube.com/watch?v=8-ZIby5U7LU)
- 📚 Plusieurs **shells** du monde Unix : Bash, Zsh... du monde Windows : cmd, PowerShell...
  
- 📰**TUI** (Textual User Interface) vs 🪟 **GUI** (Graphical User Interface)
	- GUI grand public : Macintosh (1984), Windows 3 PC (1990) 
	- serveurs, raspberry pi, ...
	- assistance IA ?
	- lancement d'applications ?
	- apprentissage ?
	- transparence des erreurs ?
	- automatisation ?
	  
- 🤔 Philosophie **UNIX**  
	-  📺 [UNIX: Making Computers Easier (1982)](https://www.youtube.com/watch?v=XvDZLjaCJuw)
	- Faire une **seule chose et la faire bien**
	- Tout est texte et/ou **fichier** 
	- Privilégie la **composition**
		- Le Tuyau (**| - Pipe**)
		- **>** (écraser) et **>>** (ajouter) vers un fichier.

- 💾 Installation
	- 🐧🍏 Linux et mac : déjà là
	- 🪟 Windows : 
		- [Git Bash](https://git-scm.com/install/windows) : le plus simple à installer (cliquer sur "suivant" lors de l'installation) 
		- [WSL](https://learn.microsoft.com/fr-fr/windows/wsl/install) : plus complet mais un peu plus dur à installer (📺 [tuto](https://youtu.be/zZf4YH4WiZo?si=8HeqwM0CLRpiksxU))
		  
- ⛵ Exercices
	- **droits** : **sudo** (super user do)
	- **naviguer** : **ls,** cd, pwd
	- **lire** : cat, less  (cat text1.txt text2.text > text3.txt)
		- **transformer** : **sed** 's/chien/chat/g' test.txt
	- **créer** : mkdir, vim, nano
	- **tâches** : ps, grep, top, htop, btop...
	- **alias** et fonctions add to .bashrc (linux, windows) or  .zshrc
		- ls -lah
	- **fonctions** : [pdf shrink](https://x.com/i/grok/share/inU0pVkgUE3SYCyLzpRL8mESo)
	- **scripts ?** .sh
	- **ssh**
	- **[git](https://git-scm.com/)** ([gitlab](https://git.unistra.fr/), [github](https://github.com/))
  