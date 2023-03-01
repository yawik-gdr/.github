# yawik-gdr

Ce projet est un fork du projet [yawik](https://gitlab.com/yawik/) pour l'adapter ua besoin de la publication des offres de thèses du [GDR GPL](https://gdr-gpl.cnrs.fr/) (offre de thèses multi-laboratoires).

Il comprend quatre repos contenant respectivement 
- le [code du backend](https://github.com/yawik-gdr/backend) modifié pour être lié à SolR afin de permettre la recherche géographique et la recherche *plain text* (backend construit à l'aide de [strapi](https://strapi.io/)). 
- le [code pour la consultation des offres d'emploi](https://github.com/yawik-gdr/jobwizard) fondé sur une [version modifiée de jobboard](https://gitlab.com/yawik/jobboard)
- le [code pour la description des offres d'emploi](https://github.com/yawik-gdr/jobboard)  fondé sur une version modifiée de [version modifiée de jobwizard](https://gitlab.com/yawik/jobwizard)
- les [éléments pour le déploiement des différentes applications](https://github.com/yawik-gdr/solrConfigAndDeployment).