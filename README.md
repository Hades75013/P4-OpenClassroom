# P4-OpenClassroom

Contexte

Vous travaillez chez « IT Consulting & Development ». C’est une petite entreprise d’une vingtaine d’employés capable de mener des projets informatiques de développement logiciel/mobile/web. Vous êtes un développeur d'application junior et, récemment, vous vous êtes également outillé pour mener l’analyse des besoins client lors des lancements de projets. Justement, ce matin, vous prenez votre courage à deux mains et vous en discutez avec Alexandra, votre responsable :

    C'est l’occasion de me confier de nouveaux projets, tu ne crois pas ? Je voudrais mettre en pratique ce que j’ai appris !

Dans la matinée, vous recevez un message d’Alexandra :

    Hey ! J’ai une demande client qui vient d’arriver, ça te dirait de te lancer sur ce projet ? C’est Lola, la co-fondatrice d’un groupe de pizzeria qui m’a contactée. Elle a besoin d’un système de gestion pour ses restaurants, mais elle n’a pas trouvé son bonheur parmi les logiciels existants. Elle nous demande donc d’en développer un sur-mesure. Nous avons discuté par téléphone et j’ai listé rapidement ce qu’elle attend de nous. Je t’envoie ça ! Peux-tu analyser sa demande et écrire le doc de spécifications fonctionnelles ?


Une minute plus tard, vous recevez ceci: 

Recueil des besoins client
Objet : Mise en place d’un nouveau système informatique pour l’ensemble des pizzerias du groupe.
Contexte : «OC Pizza» est un jeune groupe de pizzeria en plein essor. Créé par Franck et Lola, le groupe est spécialisé dans les pizzas livrées ou à emporter. Il compte déjà 5 points de vente et prévoit d’en ouvrir au moins 3 de plus d’ici 6 mois.
Le système informatique actuel ne correspond plus aux besoins du groupe car il ne permet pas une gestion centralisée de toutes les pizzerias. De plus, il est très difficile pour les responsables de suivre ce qui se passe dans les points de ventes. Enfin, les livreurs ne peuvent pas indiquer « en live » que la livraison est effectuée.
Besoins exprimés par le client :
● être plus efficace dans la gestion des commandes, de leur réception à leur livraison en passant par leur préparation ;
● suivre en temps réel les commandes passées, en préparation et en livraison ;
● suivre en temps réel le stock d’ingrédients restants pour savoir quelles pizzas peuvent encore être réalisées ;
● proposer un site Internet pour que les clients puissent :
- passer leurs commandes, en plus de la prise de commande par téléphone ou sur place ;
- payer en ligne leur commande s’ils le souhaitent
– sinon, ils paieront directement à la livraison ;
- modifier ou annuler leur commande tant que celle-ci n’a pas été préparée.
● proposer un aide-mémoire aux pizzaiolos indiquant la recette de chaque pizza
Date de livraison du système informatique :
Pour l’ouverture des 3 nouvelles pizzerias, dans 6 mois.

Comme vous voulez vraiment assurer, vous consultez Karim un collègue plus expérimenté. Vous échangez via votre plateforme de communication interne :

    Vous : Hello Karim, Alexandra vient de me confier le projet “OC Pizza”, je suis super content, ça va me permettre de faire mes preuves ! Il faut que j’écrive les spécifications fonctionnelles. Tu utilises une méthodologie particulière toi sur tes projets ?
    Karim : Génial ! Je suis content pour toi, tu le mérites ;) Perso j’ai été formé à la méthodologie UML mais ça remonte à pas mal d’années déjà ! (ah la vieillesse...) Du coup, j’utilise encore certains aspects de cette méthodologie, mais j’intègre d’autres choses car ça évolue.
    Vous : C’est-à-dire ?
    Karim : Par exemple, je trouve intéressant de définir 2-3 persona puis de rédiger un impact mapping. Cela te permet de définir les fonctionnalités selon le type d’utilisateurs. Mais j’ai gardé l’habitude d’écrire les diagrammes de cas d’utilisation UML, je trouve que c’est utile.
    Vous : Ok, merci pour tes conseils, je vais creuser par là.
    Karim: Attention ça te permet de définir une liste de fonctionnalités mais pas de l’expliquer en détail. Alexandra attend que chaque fonctionnalité soit bien détaillée dans nos dossiers de spécifications fonctionnelles (conseil d’ami ;) ).
    Vous : Il y a un formalisme particulier ?
    Karim : Chez nous non, tu peux t’inspirer de la description de scénarios selon UML ou bien de l’écriture de « User Story » selon les méthodes Agile. Il faut surtout bien détailler le chemin utilisateur, c’est-à-dire chaque étape que l’utilisateur suivra pour la fonctionnalité en question.
    Vous : Super merci beaucoup ! Je vais faire un dossier aux petits oignons grâce à ton aide !
    
    
En fin de journée, vous recevez ce mail d’Alexandra :

    Hello,

    Encore moi ! Lola vient de m’appeler (OC Pizza). Lors de la présentation du dossier de spécifications fonctionnelles qui est prévue, elle aimerait bien aborder la question de la solution technique. Je l’ai prévenue qu’en termes de timing, ce ne sera pas possible  de présenter un dossier de spécifications techniques pour ce jalon, mais qu’on lui donnera une orientation.

    Peux-tu donc inclure dans ta présentation l’annonce de la solution technique avec une courte argumentation.

    D’ailleurs, je te laisse statuer si ce serait plutôt du développement “from scratch” ou bien s’il vaut mieux partir sur la base d’un CMS e-commerce.

    Merci !

    Alexandra 

