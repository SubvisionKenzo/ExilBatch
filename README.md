# ExilBatch

This project is a software code that will simplify your life with just module and function calls... this application is notably lightweight and portable.

<br>

* [Licence](LICENCE)

<br>


#🧩 Qu’est‑ce qu’ExilBatch ?
ExilBatch est un petit SDK Windows qui permé de codé executer du code sur windows.
Il permet à n’importe quel utilisateur — même sans connaissances techniques d'apprendre une sytaxe simple pour créer des application.
VOIR : "Le code ECB" et "Fonctionnalités d’ExilBatch"

--------------------------------------------
#🎯 Pourquoi ExilBatch a été créé ?
Pour simplifier la vie des utilisateurs qui doivent souvent répéter les mêmes manipulations.

Pour rendre accessible la puissance des scripts et autres programmes sans avoir à taper plusieurs lignes de code.

Pour centraliser plusieurs outils dans une seule interface propre et intuitive.

ExilBatch existe pour ce facilité la vie dans le code et créer c'est distribution jeux facilement, pas seulement les développeurs.
--------------------------------------------
⚙️ Que fait ExilBatch concrètement ?
Il permé d'executer du code de lancer un format d'exe personnalisé .ecb avec des ressource, etre utiliser pour codé et testé du code
et plus encore...

Mises à jour régulières — Le projet évolue souvent, avec de nouvelles fonctionnalités et corrections.
--------------------------------------------
#🛠️ Fonctionnalités principales

Outils système — Accès rapide à des fonctions Windows utiles.

Interface intuitive — Tout est pensé pour être simple, même pour les débutants.

Exécution rapide — Les scripts sont optimisés pour être instantanés.

--------------------------------------------
#🚀 À qui s’adresse ExilBatch ?
Aux utilisateurs qui veulent explorer le code ce simplifier les choses et créer.

À ceux qui veulent automatiser des scripts et faire du code et applications.

Aux personnes qui veulent un outil simple et efficace.

#🧠 Comment fonctionne ExilBatch ? (explication simple)
Le logiciel contient des scripts Batch, powershell, xml.... un peut de tout !

L’utilisateur code c'est script normalement avec des commandes en plus ou simplifier peuvent créer leur exe plus facilement sous format .ECB ou compiler des scritp facillemtn bat/ps1 en exe.

ExilBatch exécute vos fichiers .ECB et c'est tout.

Le tout est présenté dans une interface claire, sans ligne de commande visible.

#Le code ECB

----------------------------------------------------------
--             A propos de la sytaxe principal          --
----------------------------------------------------------


-Syntaxe
-use.bat LIB="" FUNC="" ARG="" OUT="" MOV=""
-Fonctionnement

-use.bat est un fichier qui se charge d’interpréter 5 commandes :

-LIB=""
-FUNC=""
-ARG=""
-OUT=""
-MOV=""
-Description des arguments

-LIB=""
-L’argument LIB est utilisé pour préciser le langage de programmation ou la bibliothèque à utiliser
-(exemples : Java, Python, PowerShell, etc.).

-FUNC=""
-L’argument FUNC sert à préciser la fonction (la commande) à exécuter dans ExilBatch.
-Les commandes commencent toujours par $form. (la fonction).

-Pourquoi $form. au début ?
-Cela permet d’indiquer clairement que toutes les fonctions appartiennent au même format, et facilite leur repérage dans l’éditeur de code (moderne ou legacy) via l’outil ToolCode.

-ARG=""
-L’argument ARG sert à préciser les éléments qui composent le script.

-Exemple :

-use.bat LIB="POWERSHELL" FUNC="$form.File.Copy" ARG="C:\fichier.txt C:\dossier"

-L’interpréteur use.bat va :

-Vérifier dans son dictionnaire si la commande existe
-Trouver à quoi elle correspond

-Par exemple :

-$form.File.Copy = Copy-Item _1_ -Destination _2_

-Avec les arguments :

-ARG="C:\fichier.txt C:\dossier"

-Cela donnera :

-Copy-Item C:\fichier.txt -Destination C:\dossier

-OUT=""
-L’argument OUT sert à préciser le fichier de sortie.

-Exemple :

-OUT="test.ps1"

-(.ps1 correspond à l’extension du fichier PowerShell)

-MOV="" (optionnel)
-L’argument MOV est optionnel.
-Il sert à :

-définir le dossier de sortie du fichier
-ou combiner plusieurs scripts
-Résumé

-use.bat agit comme un interpréteur qui :

-lit une commande structurée
-la traduit selon un dictionnaire interne
-génère un script dans le langage choisi
-sauvegarde le résultat dans un fichier

----------------------------------------------------------
--             A propos des syntaxe                    --
----------------------------------------------------------

Nouvelles syntaxes : 

-use.bat LIB="" FUNC="" ARG="" OUT="" MOV=""
-AESTool.exe : (EncryptTool.exe/EncryptTool) (/Encrypt /Decrypt) ("file.txt") ("file.txt.lock") (key)                      # AES File Chiffrement
-run.bat : run.bat <C\...> <file_name>                                                                                     # Run file
-shell.bat : shell.bat file.ecb                                                                                            # Runtime
-notif.bat : notif.bat <Notification name> <title>                                                                         # Notification
-gui.bat : gui.bat file.json                                                                                               # Json UI
-  WebClient.exe /download <url> <destination>                                                                             # Outil HTML
-  WebClient.exe /download_page <url> <destination>
-  WebClient.exe /exists <url>
-  WebClient.exe /json <url>
-  WebClient.exe /progress <url> <destination>
-speak.exe /speak "" /lang "--.--"                                                                                         # Pour le dialog(vocal)
-                /speak ""

--------------------------------------------

##Fonctionnalités d’ExilBatch
-ExilBatch (ECB) est un langage basé sur Batch, Powershell, étendu avec un runtime modulaire, un système d’extensions sécurisé et un éditeur personnalisable.
-Il est léger & portable il vous donnera accès à de nombreuses fonctionnalités, telles que :
• 	Éditeur de code intégré
• 	Terminal ECB
• 	Compilateur .bat/.ps1 en .exe
• 	Compilateur de projet en .ecb
• 	Interpréteur .ecb
• 	Éditeur d’images
• 	Panneau de paramètres

# Remarques
• 	ExilBatch possède des modules de langue intégrés : Espagnol, Français, Anglais, Allemand, Russe.
• 	Le but de ce projet est de simplifier le langage informatique en permettant d’écrire du code comme ci‑dessous :
•   Il fonctionne au minimum sosu windows 7 (avec pour l'editeur legacy .NET 3.5 a installé), Windows 8/8.1, Windows 10/11 !

> [!WARNING]
> L'editeur de code a était corrrigé et refait !

> [!NOTE]
> Remarque : ExilBatch est un projet qui comport encore quelques bugs et amélioration a effectué..
> Mais les versions sont disponnible ! Pour la télécharger rendez vous sur : https://subvisionkenzo.github.io/ExilbatchWeb/

# Screenshots
![](/screenshot/screenshot1.png)
