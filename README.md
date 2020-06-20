### Why ?
---

### Requirements
---
* Node >= 12.x
* yarn = 1.12.*
* Apache 2.4
* PHP 7.3 avec extension APCu
* Mysql 5.7
* Composer
* Docker (pour le développement)

### Usage
---

### Installation
---

1. Préparer le chemin du dump SQL si vous avez un projet existant
2. Lancer la commande d'installation

```
make install
```

## Installation Front-end
```sh
PROD:
# install dependencies (yarn install && yarn encore production)
cd app/integration && yarn run start:prod
```
```sh
DEV:
# install dependencies (yarn install && yarn run encore dev)
cd app/integration && yarn run start:dev
```

### Troubleshooting
---

### FAQ
---

### Deployment
---
Lancer le déploiement sur le serveur : ```make deploy```

### Documentation
---
Docker operations :

Lancer le docker : ```make up```

Arrêter le docker : ```make stop```

Lancer le bash : ```make bash_app```

Redemarrer le docker: ```make restart```

### Authors / Maintainers
---
- Adam Chaibi
- Bruno Teboul
- Sergey Didenko
- Sofiane Souidi
- JB Pham


