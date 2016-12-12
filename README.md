# Methodologie
## Qu'est ce que ce document?
Ce document est un document Latex de méthodologie d'audit.
Il a pour objectif de formaliser les procédures d'audit suivant les différentes normes définies à travers le monde. Il ne s'agit pas d'un inventaire précis d'outil mais plutôt d'un traitement possible de l'audit.

## Pourquoi, Github?
Contrairement à l'indication de github, ce document est sous licence BSD. Il est possible de l'utiliser librement à condition de signaler le ou les auteurs.

## Options de compilation
Cette méthodologie utilise des paquets nécéssitant l'usage de la commande --shell-escape. Cette commande présente des dangers mais est ici nécessaire.

Pour MikTex, le typeset choisi doit être texify.exe --pdf --synctex=1 --tex-option=--shell-escape $fullname . A Noter que l'usage du paquet glossary nécessite l'exécution de la commande makeglossaries

# Editing Guidelines
Ce document à pour vocation d'être clair et lisible. Pour cela il est nécessaire de répondre à quelques guidelines et principes:
- Cette méthodologie est une méthodologie de haut niveau:
	- Les points abordés le sont de manière superficielle, c'est-à-dire qu'il ne s'agit pas d'un inventaire de commandes à restituer, ni d'une explication des mécanismes intrinsèques de code mais des considérations haut-niveau.
	- Les annexes peuvent contenir une approche plus technique des points et ne sont pas nécessairement afférentes aux processus d'audit
- Le choix des technologies abordées s'appuie sur l'expérience et la portabilité de ces choix
- Le choix des recommandations s'appuie sur l'expérience et la connaissance des standards.
- La mise en plage doit être facile à appréhender par l'usage des MarginNote, cette fonction doit permettre de retrouver facilement un contenu intéressant à partir d'une première lecture.
- L'édition doit utiliser si possible des éléments de référenciation (index, glossaire, titre) et considérer la possibilité d'une inclusion dans une liste en index.

