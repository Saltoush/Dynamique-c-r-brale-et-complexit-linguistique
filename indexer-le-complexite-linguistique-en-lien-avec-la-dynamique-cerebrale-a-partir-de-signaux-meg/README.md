# Indexer la complexité linguistique en lien avec la dynamique cérébrale à partir de signaux MEG

```
cd existing_repo
git remote add origin http://git.lnc.dcs.univ-amu.fr/Lucas/indexer-le-complexite-linguistique-en-lien-avec-la-dynamique-cerebrale-a-partir-de-signaux-meg.git
git branch -M main
git push -uf origin main
```
***

## Name
Complexité linguistique et Dynamique cérabrale

## Description
Ce git correspond aux implémentations de l'algortihme mis en place durant mon stage de fin d'étude d'école d'ingénieur au Laboratoire de Neurosciences Cognitives de Marseille. On y traite la dynamique cérébrale grâce à des méthodes de la théorie de l'information et des systèmes dynamiques en se basant sur une mesure MEG de l'activité cérébrale. Cela dans le but d'indexer, la complexité cérébrale, de pouvoir discriminer des conditions expérimentales grâce à la métrique qu'est le taux d'entropie d'une séquence symbolique.
Tout est détaillé dans mon rapport de stage. Les expérimentatations ont été effectuées sur la base de données MOUS, disponible en ligne.

Algo_partition correspond à une première méthode de représenation symbolique. Algo_phase_cluserisation à une seconde méthode de représentation symbolique. 
Algo_entropie_phrase permet de calculer l'entropie au cours du temps avec les marqueurs temporels correspondants aux différents stimuli (phrase simple, phrase complexe, liste aléatoire de mots).

## Installation
Les packages nécessaires pour reproduire mon travail sont compilés dans requirements.txt.
Il est également nécessaire d'avoir le module scikits-symbolic disponible à cette adresse http://git.lnc.dcs.univ-amu.fr/lpezard/scikits-symbolic/ pour pouvoir utiliser mes codes.

## Support
Si vous ayez besoin d'aide ou que vous voulez me contacter, cela est possible via courriel : lucas.becquet@centrale-marseille.fr.

## Contributing
Mon stage est à présent terminé mais rien ne vous empêche d'utiliser mon code, de l'améliorer ou d'apport de nouvelles contributions. Les perspectives futures sont détaillées dans la conclusion de mon rapport de stage.

