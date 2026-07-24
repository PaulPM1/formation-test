# formation-test

Dépôt d'entraînement Git / GitHub.

## À quoi ça sert

Ce dépôt est un bac à sable créé dans le cadre d'une formation. Il sert à
pratiquer les gestes de base d'un workflow Git :

- cloner un dépôt distant,
- créer une branche,
- modifier des fichiers et faire un commit,
- pousser (`push`) vers GitHub,
- ouvrir une pull request.

Il ne contient volontairement aucun code applicatif — juste ce README.

## Workflow de base

```bash
# 1. Cloner le dépôt
git clone https://github.com/PaulPM1/formation-test.git
cd formation-test

# 2. Créer une branche de travail
git checkout -b ma-branche

# 3. Modifier un fichier, puis enregistrer les changements
git add .
git commit -m "Décris ici ce que tu as changé"

# 4. Pousser la branche vers GitHub
git push -u origin ma-branche
```

Ensuite, ouvre une pull request depuis l'interface GitHub pour proposer la
fusion de ta branche dans `main`.

## Notes

- Dépôt public, à usage pédagogique.
- N'hésite pas à casser des choses : c'est fait pour ça.

---

*Dernière mise à jour : 24 juillet 2026*
