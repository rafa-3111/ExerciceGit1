***** Ce que j'ai fait *****
Participant : Jocelyn Tétreault
1- grace à github desktop
  a- j'ai créer un ropository su mon ordi local
  b- cloner le liens offert dans le copy to clipboard ce qui a copier la version serveur
2- grace à Git Bash que j'ai fait ouvrir directement sur le bon repertoire voicie une copie d'écran des opérations
3- Et je l'ai retourner sur mon serveur pour pouvour vous y donner acces

*** Copy/Paste de l'espace de travail "Git Bash" *****

Jocelyn Tétreault@MsiZ97G43 MINGW64 /t/Projets/Developpement/CodeBoxx/Traveaux
$ git clone https://github.com/MathieuHoude/ExerciceGit1.git CodeBoxx_Exercice-Git-01
Cloning into 'CodeBoxx_Exercice-Git-01'...
remote: Enumerating objects: 83, done.
remote: Counting objects: 100% (83/83), done.
remote: Compressing objects: 100% (69/69), done.
remote: Total 187 (delta 5), reused 74 (delta 1), pack-reused 104
Receiving objects: 100% (187/187), 32.21 KiB | 3.58 MiB/s, done.
Resolving deltas: 100% (15/15), done.

Jocelyn Tétreault@MsiZ97G43 MINGW64 /t/Projets/Developpement/CodeBoxx/Traveaux
$ cd CodeBoxx_Exercice-Git-01

Jocelyn Tétreault@MsiZ97G43 MINGW64 /t/Projets/Developpement/CodeBoxx/Traveaux/CodeBoxx_Exercice-Git-01 (master)
$ ls
helloworld.txt  README.md

Jocelyn Tétreault@MsiZ97G43 MINGW64 /t/Projets/Developpement/CodeBoxx/Traveaux/CodeBoxx_Exercice-Git-01 (master)
$ dir
helloworld.txt  README.md

Jocelyn Tétreault@MsiZ97G43 MINGW64 /t/Projets/Developpement/CodeBoxx/Traveaux/CodeBoxx_Exercice-Git-01 (master)
$ echo "hello world"
hello world

Jocelyn Tétreault@MsiZ97G43 MINGW64 /t/Projets/Developpement/CodeBoxx/Traveaux/CodeBoxx_Exercice-Git-01 (master)
$ echo "Hello world -- JT" >> ./test

Jocelyn Tétreault@MsiZ97G43 MINGW64 /t/Projets/Developpement/CodeBoxx/Traveaux/CodeBoxx_Exercice-Git-01 (master)
$ echo "Hello world -- JT" >> ./test

Jocelyn Tétreault@MsiZ97G43 MINGW64 /t/Projets/Developpement/CodeBoxx/Traveaux/CodeBoxx_Exercice-Git-01 (master)
$ cat ./test
Hello world -- JT
Hello world -- JT

Jocelyn Tétreault@MsiZ97G43 MINGW64 /t/Projets/Developpement/CodeBoxx/Traveaux/CodeBoxx_Exercice-Git-01 (master)
$ cat ./helloworld.txt
Hello World -- MH

Jocelyn Tétreault@MsiZ97G43 MINGW64 /t/Projets/Developpement/CodeBoxx/Traveaux/CodeBoxx_Exercice-Git-01 (master)
$ echo "Hello world -- JT" >> ./helloworld.txt

Jocelyn Tétreault@MsiZ97G43 MINGW64 /t/Projets/Developpement/CodeBoxx/Traveaux/CodeBoxx_Exercice-Git-01 (master)
$ cat ./helloworld.txt
Hello World -- MH
Hello world -- JT

Jocelyn Tétreault@MsiZ97G43 MINGW64 /t/Projets/Developpement/CodeBoxx/Traveaux/CodeBoxx_Exercice-Git-01 (master)
$ dir
helloworld.txt  README.md  test

Jocelyn Tétreault@MsiZ97G43 MINGW64 /t/Projets/Developpement/CodeBoxx/Traveaux/CodeBoxx_Exercice-Git-01 (master)
$ rm test

Jocelyn Tétreault@MsiZ97G43 MINGW64 /t/Projets/Developpement/CodeBoxx/Traveaux/CodeBoxx_Exercice-Git-01 (master)
$ dir
helloworld.txt  README.md

Jocelyn Tétreault@MsiZ97G43 MINGW64 /t/Projets/Developpement/CodeBoxx/Traveaux/CodeBoxx_Exercice-Git-01 (master)
$ git add .
warning: LF will be replaced by CRLF in helloworld.txt.
The file will have its original line endings in your working directory

Jocelyn Tétreault@MsiZ97G43 MINGW64 /t/Projets/Developpement/CodeBoxx/Traveaux/CodeBoxx_Exercice-Git-01 (master)
$


je ne peux monitorer 
git commit -am "lire readme pour plus de detail"
git push

sinon ce fichier ne serais pas updater

**********
+-----------------------------------------------------------------------------------------+
| Vous remarquerez que J'ai inclus la validation du fonctionnement                        |
| Et aussi pris soint de respecter à 100% le format (Majuscule, Minuscule, et espacement) |
| du travail déja effectuer sur le fichier et de terminer en supprimer les tests devenue  |
| inutile. En plus de fournir un documentation maximal du travail effectuer.              |
|                                                                                         |
| espérant que le tous sauras répondre au besoins exprimer.  Jocelyn Tétreault            |               
+-----------------------------------------------------------------------------------------+


# Exercice Git #1
## Clone, Branch, Add, Commit, Push

Pour cet exercice vous devez modifier le fichier helloworld.txt pour y ajouter votre propre Hello World avec vos initiales.

Le fichier txt doit être modifié **uniquement à l'aide du CLI de votre choix**. Donc pas le droit de seulement modifier le fichier dans un éditeur.
En dessous de votre HelloWorld, mentionnez quel outil vous avez utilisé pour y arriver.

Il faudra ensuite retourner le fichier modifié sur votre propre branche, toujours sur mon repo. Simplement m'écrire en PV avec votre Username GitHub pour que je puisse vous ajouter comme collaborateur. Vous recevrez alors un courriel d'invitation à devenir collaborateur et une fois acceptée vous pourrez ensuite faire un push.


### Ne pas faire de push sur le master!
### Le tout doit être fait en utilisant seulement votre CLI, donc sans l'application GitHub, sans l'option download zip, etc.

---------------------------------------------------------------------------------------------------------------------------------
# Git Exercice #1
## Clone, Branch, Add, Commit, Push

For this exercise you must modify the helloworld.txt file to add your own Hello World and your initials.

The txt file should be edited **only using the CLI of your choice** and not in an editor.
Below your HelloWorld, mention which tool you used to make it happen.

You will then have to return the modified file to your own branch, still on my repository. Simply write to me in PV with your GitHub Username so that I can add you as a collaborator. You will then receive an email invitation to become a collaborator, which once accepted will allow you to do a push.


### Don't make any push on the master branch!
### All of this needs to be done using only you CLI, so no Github application, no Download Zip, etc.
