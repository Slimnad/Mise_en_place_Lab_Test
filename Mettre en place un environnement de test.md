**Mettre en place un environnement de test (Lab)**


    Vérification des intégrités des images téléchargées avant installation.
Avec la commande "sha512sum" pour debian (linux).
Avec la commande "Get-fileHash" pour windows (Powersell).


    Après installation et mise à jour des 3 machines virutelles (Srv win AD, win client et debian).
Par la suite mise en place des différents services :
- DNS (celui par defaut du domaine)
- WEb (VulnerableLightApp)
- SSH et WinRM (accessible uniquement aux administrateurs Windows et Linux)
- Partage SMB (1 en "readonly" pour tous et un en lectur écrutire "rw" sur le serveur Windows)

**Status DNS**

url

**Connexion SSH (Debian)**

url

**Connexion WinRM (Windows)**

url

**Paratage SMB**

urls

**Status Web**

url

    Enfin lancement du script badblood ./invoke-badblood.ps1

**Nombre d'utilisateurs AD après script**

url

