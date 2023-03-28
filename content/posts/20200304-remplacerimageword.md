---
title: "Chercher/Remplacer des images dans Word"
date: "2020-03-04T12:08:00-05:00"
tags: [automagiquement, Word, rechercher/remplacer, image]
toc: true
---

Petit truc qui m’a bien servi une fois où je devais remplacer toutes les instances d’un logo dans une liste d’étiquettes montée en Word (gabarit Avery). Au lieu de remplacer chaque image manuellement (il y en avait une bonne centaine!), j’ai pu tout remplacer en quelques clics seulement.

Il faut d’abord remplacer une des images et copier cette nouvelle instance. Puis, dans la fenêtre Rechercher et Remplacer, utiliser les codes suivants : 
- Rechercher : ^g (= image)
- Remplacer par : ^c (= contenu du presse-papier)

![capture](../images/1nfograph3/word-chercherremplacer-images.png)

Bien sûr, ce truc ne peut fonctionner que si toutes les images sont pareilles dans l’ensemble du document puisque le code s’applique à toutes images confondues. On peut aussi penser s’en servir sur du texte, pour formater un mot et le mettre en évidence partout où il apparaît dans le document puisque le presse-papier conserve aussi le style appliqué au texte copié.

[Source : The Windows Club](https://www.thewindowsclub.com/find-and-replace-all-images-in-word)
