## Commandes BASH - Projet scolaire

Réalisation de script bash :
- **bin2dec :** Convertisseur de nombres binaires (binary to decimal)
```
./bin2dec 10
bin2dec(10)=2```
- **cut_mail :** Programme qui coupe des mbox
```
./cut_mail mbox destdir
```
- **factorial :** Calcule le factoriel d'un nombres
```
./factorial 5
120
```
- **replace :** Remplace une chaine de caractère dans un fichier
```
./replace originFile replaceFile File
```
- **killall :** Tue les processus
```
./killall option
options:
-user user1 : Kill all processes for user1
-pid pid1  : Kill a process with pid pid1
-prog prog1 : Kill all processes whose programs name is prog1
-all : Kill all processes
```
- **primary :** Affiche les n premiers nombres premiers
```
./primary 5
2 3 5 7 11 13
```
- **tree :** Affiche la structure du dossier
```
./tree dirName
```
- **upcase_lowcase :** Convertit soit en majuscule soit en minuscule
```
echo "bonjour" | ./upcase_lowcase -u
BONJOUR
echo "BONJOUR" | ./upcase_lowcase -l
bonjour
```
- **db :** met a jour un fichier
```
./db file
```
