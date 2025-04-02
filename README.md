TODO :

- [x] Avoir les boards de base d'un kanban
- [x] Déplacer les tickets
- [x] Créer des tickets
- [x] Voir le détail des tickets
- [x] Supprimer des tickets
- [x] Bouton d'export du dataset pour l'instant (pour une recompilation futur)

Pour lancer le projet faut créer un fichier src/dataset/kanban.json sous cette forme :

```
{"tables":[{"id":0,"name":"A faire","cards":[]},{"id":1,"name":"En cours","cards":[]},{"id":2,"name":"Finit","cards":[]}]}
```