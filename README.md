# Noctis — publications

Ce dépôt ne contient **aucun code**. Il ne sert qu'à deux choses :

- porter les installeurs de [Noctis](https://github.com/JulienBois/Noctis),
  un lecteur vidéo pour Windows ;
- servir le fichier que l'application interroge pour savoir si une version
  plus récente existe.

## Mettre à jour Noctis

Dans l'application : **Préférences → Mises à jour**, coller cette adresse.

```
https://julienbois.github.io/noctis-releases/latest.json
```

Elle ne change jamais — c'est tout l'intérêt de la servir depuis GitHub Pages
plutôt que depuis une publication, dont l'adresse porterait le numéro de
version et serait donc à corriger à chaque fois.

## Installer

Le dernier installeur se trouve dans les
[publications](https://github.com/JulienBois/noctis-releases/releases).

Chaque installeur est signé. L'application vérifie cette signature avec la clé
publique inscrite dans son binaire, et refuse une mise à jour qui ne
correspondrait pas.
