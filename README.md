# Checklist sécurité pour les applications web

Objectif : Fournir une liste de recommendations liées à la sécurité des applications web à destination des développeurs et pentester

Cette checklist est décomposée en trois parties : **Frontend**, **Backend** et **Infrastructure**

Les recommendations de sécurité sont classées en deux groupes :

- <span style="color:red">En rouge</span> ![#f03c15](https://via.placeholder.com/15/f03c15/f03c15.png), les recommendations critiques.

- <span style="color:blue">En bleu</span> ![#1589F0](https://via.placeholder.com/15/1589F0/1589F0.png), les recommendations souhaitables.


***


## Frontend

- [ ] ![#f03c15](https://via.placeholder.com/15/f03c15/f03c15.png) L'application est accessible via https
- [ ] ![#1589F0](https://via.placeholder.com/15/1589F0/1589F0.png) HSTS est mis en place via le header strict-transport-security
- [ ] ![#f03c15](https://via.placeholder.com/15/f03c15/f03c15.png) Les modifications dynamiques du dom via javascript utilisent de préférence la balise html template au lieu des template strings es6
- [ ] ![#f03c15](https://via.placeholder.com/15/f03c15/f03c15.png) Les modifications du dom n'utilisent pas innerHTML lorsque cela est possible ( par exemple textContent ).
- [ ] ![#f03c15](https://via.placeholder.com/15/f03c15/f03c15.png) La fonction javascript eval() n'est pas utilisée.
- [ ] ![#f03c15](https://via.placeholder.com/15/f03c15/f03c15.png) Aucune données sensible n'est stockée via localStorage, indexedDb ou cookie.
- [ ] 


## Backend

## Infrastructure
