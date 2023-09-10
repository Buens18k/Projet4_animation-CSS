# ***<u> " OhMyFood - Paris" </u>***
## ***<u> Formation OpenClassRoom</u> " Intégrateur Web "***.   
### <u> Projet 4 :</u> ***" Améliorez l'interface d'un site mobile avec des animations CSS".*** 
> ***<u>Scénario :</u>***<br> Vous avez intégré Ohmyfood en tant que développeur junior. Il s’agit d’une jeune startup qui voudrait s'imposer sur le marché de la restauration. Déjà présente à New-York, elle souhaite désormais faire sa place à Paris. 

> ***<u>Mission :</u>***<br> 
**Développer un site “mobile first”** qui répertorie les menus de restaurants gastronomiques. <br>
En plus des systèmes classiques de réservation, les clients pourront composer le menu de leur repas pour que les plats soient prêts à leur arrivée. Finis, les temps d'attente au restaurant !<br>
L’équipe commerciale a déjà réussi à convaincre ***4 restaurateurs*** d’utiliser la plateforme ***<u>OhMyFood***</u>. Paul décide alors que le site contiendra ***<u>4 menus</u>*** dans un premier temps.<br>
À deux, vous avez pu établir [<u>ce brief créatif</u>](https://course.oc-static.com/projects/D%C3%A9veloppeur+Web/IW_P4+Animations+CSS+Ohmyfood/Brief+creatif+site+Ohmyfood.pdf) pour rassembler toutes les informations clés du projet de développement du site.<br>
Le projet va pouvoir commencer. Paul vous envoie les maquettes par e-mail :<br> <pre>Objet : Maquettes site OhMyFood Paris   
De : Paul   
À : moi <br>
Bonjour !<br>
L’UX designer a finalisé les maquettes mobile et desktop du site !<br>
Tu les trouveras en pièce jointe, en plus du dossier des sources du site (images et textes).<br>
Tu y trouveras également le prototype du site via Figma, incluant les animations et comportements à intégrer.<br>
Voici un extrait de ce à quoi devra ressembler le site :<br>
![](https://lh3.googleusercontent.com/pw/AIL4fc8o6ixwf3N0uZ8F0sUhKiDLKzd7Kl4b9nSco42MdEj87bUlmR5gwDBC1tw3_LypnesJm9sCQ6yf9731Fxi0Ov9UtvETlmIxk2rS0rHBLOoheXULMkuhSzhPBdU8GRxn77TdaXBCffcLyGuIpdLmILdNwYqjqJfe4jncJJnUzmeQrY8bH5BY-jGbDpWqcUOwoMd8f2tFYwEk2f_262fgMURCdA8zm6ERLuOIM6xcHA0TtWI2imRKxbIrt2QgMBEGDUvA4R1X9p4dO6OW4hoSlxdaVYdkeEftSUaIIYyJxkKw8w_GeZWPkkZJjLtDt4Y7s_WnMIfGpy4QK5opQ65oFbdV4yVIp6Lur91Zv8zDpHZhA2R8HqGngPF81jlIklksBqO1RYHzWnyfXhEFZFExvmChfyxalsoR6a6GGULyfIOTUtkbOUW0CfUvcMlHBTDUZYhV3BIp7BazKD-oZqz-T_1WHp7onZdNbNX2OW7F2dUcNo0oBGXklSgmJ9ThBfVe-8LEPxkuL4IEnAGQYFdcJAFSc7HTOz7vN5SfY4aE28cHTYlT8ylua3nNFFgBmuqCySRa2lYl22V--0kfRxopd81StwJyk6Yax2bQrw-Wr1yAVFCaxDTP-zr-AKt3sIbKTOxKbB3P2rStp6s0s-PxWpd3YEZ2flLY40WDbSj0QqDiKZLBnImYBn5_mBW3gh4a8gMA7IK4r4x8sKV1ynboXVQADh2DNTuNITdGtd7n1ZX1JiR_ezLVy9Jh2bSEJOnx36Nsh5t1B68fheutA6PdXmtsCi2_J_h5-Tn42gs6juQOxoFausp94nCrDx9_8CiSoB1ODpz3Txguk2lnnGpIKEjsjWsXirFW3mjy0OVhFovdzG4cSSv-GXpM_ZKDHib8OABvzLvTlTACfY6hvctYG3wewnFkFdQvf8jylPgdOhVH7M405dwkdXm-1VZ31j-sx5awEIqVno_r3B-ltYxU9-zIBvxfmg=w593-h287-s-no?authuser=0) <br>
Il n’y a plus qu’à le développer pour mobile, tablette et desktop en s’appuyant rigoureusement sur les informations déterminées dans le brief créatif !<br>
Pour rappel, le site doit être responsive et en “mobile first”.<br>
On veut aussi des animations soignées. Il faudra que tu m’expliques comment elles fonctionnent.<br>
Hâte de voir le site terminé !<br>
Bon courage !<br>
Paul<br>
Pièce jointe :
[<u>Maquettes mobile et desktop du site Ohmyfood </u>](https://www.figma.com/file/t4449fzDnwGYmzuwQdu87V/Maquettes-Ohmyfood-(mobile-et-desktop)?node-id=0%3A1&mode=dev)
[<u>Prototype du site</u>](https://www.figma.com/proto/t4449fzDnwGYmzuwQdu87V/Maquettes-Ohmyfood-(mobile-et-desktop)?node-id=25368-591&scaling=scale-down&page-id=0%3A1&starting-point-node-id=25368%3A591&show-proto-sidebar=1) 
[<u>Fichiers sources (images et textes)</u>](https://drive.google.com/file/d/123vPuBPEAYODupm-42PjYmLwb4N0kyaL/view?usp=sharing)<br>
Vous avez désormais tous les éléments pour construire le site. Vous vous lancez dans cette nouvelle aventure !
</pre>

## <u>***Compatibilité***</u> ##
La cible étant les personnes connectées et pressées, le site est donc développé en utilisant l’approche ***Mobile-first***.<br>
Le site est donc intégré en suivant les maquettes mobile, puis le responsive suit pour les tablettes et ordinateurs en suivant les maquettes données par le designer.<br>
● L’ensemble du site est responsive sur mobile, tablette et desktop.<br>
● Les pages sont passer à la validation W3C en HTML et CSS.<br>
● Le site est parfaitement compatible avec les dernières versions desktop de Chrome et Firefox.

## <u>***Technologies***</u> ##
● HTML.<br>
● CSS, Méthodologie BEM.<br>
● Pré-processeur Sass, pas de JavaScript.<br>
● Structuration Sass avec le système d'architecture 7-1.<br>
● NPM (Node Package Manager) pour la gestion des dépendances et l'automatisation des tâches de développement.<br>
● Code versionné sur GitHub avec l'extension Gitflow.<br>


## <u>***Gestion des Dépendances***</u> ##
Ce projet utilise ***NPM (Node Package Manager)*** pour gérer ses dépendances.<br>
Node.js est nécéssaire pour exécuter NPM. <br>
Assurez-vous d'avoir Node.js installé localement pour travaillez avec ce projet.

## <u> ***Script de construction*** </u> ##
Ce projet utilise des scripts de construction pour gérer les fichiers SCSS et générer le CSS.<br>
<u> Voici comment les utiliser : </u>

- **dev** : Utilisez ce script pendant le développement. Il surveille les modifications dans le fichier <u>'main.scss'</u> et compile automatiquement le SCSS en CSS chaque fois qu'une modification est détecter.<br>
Pour lancer le mode développement, exécutez :
>npm run dev

- **build** : Utilisez ce script pour générer une version finale et optimisée du CSS pour la production ou le déploiement.<br>
Il ne surveille pas les modifications en temps réel.<br>
Pour générer la version de production, éxécutez :

> npm run build

Assurez-vous d'avoir Node.js et NPM installés localement pour éxécuter ces scripts.


## <u> ***Accès au site*** </u> ##

Le site est accessible sur GitHubPages via cette adresse ci-dessous :<br>
> ***https://buens18k.github.io/Projet4_animation-CSS/***
