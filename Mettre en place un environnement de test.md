**Mettre en place un environnement de test (Lab)**


    Vérification des intégrités des images téléchargées avant installation.
Avec la commande "sha512sum" pour debian (linux).
Avec la commande "Get-fileHash" pour windows (Powersell).

![alt tag](https://github.com/Slimnad/Mise_en_place_Lab_Test/blob/main/HASH_deb.png?raw=true)

    Après installation et mise à jour des 3 machines virutelles (Srv win AD, win client et debian).
Par la suite mise en place des différents services :
- DNS (celui par defaut du domaine)
- WEb (VulnerableLightApp)
- SSH et WinRM (accessible uniquement aux administrateurs Windows et Linux)
- Partage SMB (1 en "readonly" pour tous et un en lectur écrutire "rw" sur le serveur Windows)


**Status DNS**

![alt tag](https://github.com/Slimnad/Mise_en_place_Lab_Test/blob/main/StatuDNS.png?raw=true)

**Connexion SSH (Debian)**

![alt tag](https://github.com/Slimnad/Mise_en_place_Lab_Test/blob/main/SSH.png?raw=true)

**Connexion WinRM (Windows)**

![alt tag](https://github.com/Slimnad/Mise_en_place_Lab_Test/blob/main/WinRM.png?raw=true)

**Paratage SMB**

![alt tag](https://github.com/Slimnad/Mise_en_place_Lab_Test/blob/main/SMB1.png?raw=true)

![alt tag](https://github.com/Slimnad/Mise_en_place_Lab_Test/blob/main/SMB2.png?raw=true)

**Status Web**

![alt tag](https://github.com/Slimnad/Mise_en_place_Lab_Test/blob/main/statuWEB.png?raw=true)

    Enfin lancement du script badblood ./invoke-badblood.ps1

**Nombre d'utilisateurs AD après script**


![alt tag](https://github.com/Slimnad/Mise_en_place_Lab_Test/blob/main/userAD2.png?raw=true)


![alt tag](https://github.com/Slimnad/Mise_en_place_Lab_Test/blob/main/userAD1.png?raw=true)

