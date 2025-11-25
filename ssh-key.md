
- **Vérifier que vous n'avez pas déjà une clé ssh**
	-  Pour vérifier dans un terminal : `ssh-add -l`
- **Sinon il faut en créer une** 
	-  `ssh-keygen -t ed25519 -C "your_email@example.com"` 
		- ne pas entrer de pass phrase pour simplifier 
		  (sinon il faut gérer un ssh-agent pour ne pas la tapper à chaque fois )
- **Localisation des clés** en local
	- `Linux	/home/USERNAME/	~/.ssh/	id_ed25519.pub or id_rsa.pub`
	- `macOS	/Users/USERNAME/	~/.ssh/	id_ed25519.pub or id_rsa.pub`
	- `Windows	C:\Users\USERNAME\	%USERPROFILE%\.ssh\	id_ed25519.pub or id_rsa.pub`
- **Copier votre clé public dans** :
	- **github** : votre portrait > settings > SSH > "new SSH key" (copier/coller)
	- **gitlab** : votre portrait > préférences > SSH > "add new key" (copier/coller)
- **Changer un dossier** déjà gérer par git via https **vers ssh**
	- ouvrir un terminal dans le dossier en question : 
		- `git remote set-url origin git@github.com:username/your-repository.git `
- **Ressources**
	- [Generating a new SSH key and adding it to the ssh-agent]()
	