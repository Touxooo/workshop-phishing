# Workshop Phishing

## Disclaimer
**Attention**, les informations que vous allez acquérir servent **uniquement** dans le cadre de l'éducation.
**L’hameçonnage** ou **phishing** est une technique utilisée par des fraudeurs pour obtenir des renseignements personnels dans le but de perpétrer une usurpation d'identité.
Cette **pratique** est très simple à mettre en place, donc soyez **vigilants**!


## Technologies à utiliser

- **HTML/CSS** (pas besoin d'installation)
 - **PHP** (à installer depuis votre gestionnaire de paquet)

Les technologies vont être utilisées pour créer une simple page de phishing, cependant il n'est pas nécéssaire d'avoir des compétences techniques sur ces technos.

## Exercices
### Exercice 1
Créer une simple page web HTML avec un formulaire contenant deux inputs : email et password, ainsi qu'un bouton submit. **Attention**, utilisez bien la balise **\<form>**!

![](https://i.imgur.com/HgWxneR.png)


### Exercice 2
Créer un fichier **PHP** qui récupère les informations données dans le formulaire créé précédément. Vous devez obligatoirement lier le **\<form>** au script PHP, et y ajouter le méthode **POST**. Ensuite, faites en sorte que les **identifiants** récupérés dans le PHP s'affichent après avoir cliqué sur le bouton **Submit**.
Pour **tester** votre programme, utilisez la commande suivante à la racine de votre projet: ```php -S localhost:[PORT]```, mettez le port que vous souhaitez (ex: 6969) à la place de **[PORT]**

### Exercice 3
**Maintenant** qu'on arrive à afficher les **identifiants**, il serait utile de pouvoir les **stocker**, pour ainsi pouvoir les consulter quand on veut. **Améliorez** le script pour y ajouter cette **fonctionnalité**, puis en **ajoutant** la **date et heure** de la récupération d'identifiants

### Exercice 4
Évidemment,  avec un site web comme ça, une personne un minimum méfiante ne rentrerait pas ses informations personnelles. Alors, pour que le phishing fonctionne, il faut se faire passer pour **quelqu'un** ou **quelque chose**. Admettons qu'une personne veuille récupérer vos identifiants personnelles **Instagram**, alors elle vous enverra un lien vers une **fausse page de connexion** Instagram en espérant que vous tombiez dans le piège.
La **particularité** des sites web, est que le code source peut être affiché en quelques clics, donc très facilement **copiable**.
Dans ce cas, prennez une page de connexion d'un site web et essayez de le recopier sur votre machine.

### Exercice 5
On a vu comment créer un script PHP et le lier dans notre page HTML, maintenant faites de même sur la page HTML que vous venez de **télécharger**. Pensez-bien à la balise **\<form>**! :wink:
Pour **améliorer** le piège, vous pouvez rajouter un **lien de redirection** sur la page officiel de votre site de référence dans votre script PHP.

### Exercice 6
**Stocker** les identifiants c'est **bien**, mais il faut souvent vérifier le fichier où sont stockés tous les identifiants personnels. Alors, **pour aller plus loin**, vous pouvez vous renseigner sur les **webhooks Discord et PHP** pour implémenter un système de notification. Vous ferez en sorte que dès que quelqu'un se fait **piéger** sur votre fausse page de connexion, un **bot Discord** vous envoie le détail du piège sur votre propre **serveur Discord**.
```
