# Méthode adaptée au raffinement conversationnel

## Adapter au domaine et au résultat recherché
Appliquer [les postures de raffinement](postures.md) selon l'objectif métier. L'approche développement reste approfondie et conserve ses angles actuels; l'élargissement aux autres métiers ne doit pas l'affaiblir. Le socle commun est la confrontation des sources, les questions ciblées et la distinction faits/hypothèses/décisions, pas une grille uniforme de questions.

Accepter une idée encore embryonnaire aussi bien qu'un billet élaboré. Déterminer le domaine à partir de la demande; clarifier ce qui est nécessaire sans imposer un questionnaire d'accueil. Pour une demande métier, organisationnelle ou de communication, partir du problème, des bénéficiaires, du changement attendu et des critères de succès. L'absence de requis formels ou de wireframe n'est pas une lacune à combler par défaut.

Se concentrer sur les objectifs et les résultats observables. Distinguer les contraintes déjà confirmées des choix de solution encore ouverts. Laisser les technologies, l'architecture et les détails de réalisation aux responsables concernés. Une dépendance technique peut être signalée si elle change la portée ou la validation; demander alors son effet attendu, pas un choix d'implémentation. Une tâche technique explicite reste une tâche technique, sans bénéfice métier inventé.

## Confronter les sources
Pour chaque résultat ou comportement important, relier intention → règle ou contrainte confirmée → représentation dans les sources si applicable → COS ou critère de succès. Pour une idée, construire progressivement ce lien à partir des réponses; ne pas inventer les éléments absents. Repérer les éléments absents ou incompatibles sans imposer une matrice à l'utilisateur. Conserver la provenance des décisions : texte du billet, requis identifié, COS identifié, écran/zone, réponse utilisateur. Sans identifiants, utiliser des repères descriptifs; ne pas inventer de numéros de lignes ou de zones.

Un wireframe montre des éléments et des parcours possibles; il ne confirme pas à lui seul les permissions, les calculs, les états d'erreur, la persistance ou les règles cachées. Si la hiérarchie des sources est connue, l'appliquer; sinon questionner la contradiction pertinente.

## Angles d'analyse
En développement, ces angles constituent la grille de raffinement à examiner selon les surfaces touchées; conserver la profondeur utile aux requis et COS. Dans les autres métiers, sélectionner ou remplacer les angles selon la posture décrite dans la fiche dédiée.

- Intention : quel problème, pour qui, quel changement observable, quel résultat constitue un succès? Distinguer demande de solution et besoin, sans rejeter une contrainte de solution confirmée.
- Métier : permissions, admissibilité, règles de calcul, exceptions, priorités entre règles, responsabilité des décisions.
- Parcours ou processus : situation actuelle, changement attendu, étapes, intervenants, exceptions et résultat partiel. Pour une interface seulement : navigation, annulation, reprise, premier usage, chargement, vide, succès et erreur si pertinents.
- Informations et données : éléments nécessaires à la décision ou au résultat, provenance, disponibilité et fiabilité. Examiner conservation, doublons ou migration seulement si le besoin les touche; ne pas concevoir leur stockage.
- Temps et concurrence : dates limites, fuseaux, publication, expiration, actions simultanées, double soumission si pertinents.
- Impacts : personnes, équipes, activités et processus concernés; dépendances connues ou à vérifier. Ajouter produits, écrans, systèmes ou APIs uniquement si la demande les touche, au niveau de leur effet sur le résultat.
- Qualité et succès : conditions qui rendent le résultat utile et vérifiable dans le domaine concerné. Pour un service numérique, examiner accessibilité, sécurité, performance ou exploitation selon les risques concrets et leurs effets observables; ne pas choisir les mécanismes techniques. Ne pas parcourir toutes les rubriques pour chaque billet.
- Validation : les COS démontrent-ils le résultat voulu? Peut-on tous les réussir et malgré tout manquer le besoin? Les exemples positifs, négatifs et limites utiles sont-ils définis?
- Portée : plus petite tranche utile; exclusions réelles; éléments pouvant rester négociables. Préserver les exigences de qualité indispensables.

## Choisir les prochaines questions
Ordre indicatif : contradiction qui bloque la compréhension; objectif ou règle qui change le résultat; comportement absent à impact élevé; validation insuffisante; détails secondaires. Adapter selon le risque concret et les réponses reçues. Aucun score artificiel n'est nécessaire.
Une question puissante rend visible une conséquence ou un arbitrage : « Le COS prévoit X, alors que le requis demande Y. Quel comportement doit prévaloir dans ce cas? »
Préférer un scénario concret à « Peux-tu préciser? ». Lorsqu'une règle reste abstraite, demander d'abord un exemple; demander un contre-exemple dans un tour suivant seulement si nécessaire. Ne pas interpréter systématiquement « peut-être » comme un blocage : distinguer option, incertitude et engagement.

Poser une seule question par tour, puis attendre la réponse. Ne pas dissimuler plusieurs décisions dans une question composée. Adapter la prochaine question à ce qui vient d'être confirmé. Quand les alternatives sont utiles, proposer deux à quatre choix au maximum, plus « Autre — précise », dans une interface interactive adaptée ou une liste courte. Conserver la réponse ouverte quand les options ne rendent pas justice au besoin.

## Séparer confirmation et proposition
Un choix plausible issu d'une référence reste une suggestion. Les defaults du corner-checklist ne sont pas des décisions autorisées. Les comportements métier, permissions, pertes de données acceptables, seuils, obligations et arbitrages doivent être confirmés. Présenter toute proposition non validée comme telle et l'exclure des requis confirmés. Une règle issue d'une source externe reste à confirmer pour ce produit.

## Cadrage de la conversation
Avant la première question, annoncer les aspects à raffiner dans un plan bref en puces, adapté au billet, avec une cible indicative de questions fondée sur les incertitudes restantes (par exemple 4 à 6 pour un récit ciblé). Ne pas faire de cette cible un quota ou une promesse, ni annoncer 20 comme horizon habituel. Poser ensuite la première question sans demander de confirmer le plan. Indiquer à chaque question son numéro et l'aspect du plan abordé, par exemple « Question #4 · Objectif et portée ». Le plafond de 20 reste suivi sans afficher « /20 ». Le compteur suit le même billet, y compris les relances et les clarifications; une synthèse intermédiaire ne le réinitialise pas.

Garder 20 comme plafond exceptionnel. Avant chaque question, identifier la décision qui changerait selon la réponse; écarter les questions sans effet sur l'objectif, la portée, un comportement, un critère de succès, une règle déterminante ou les frontières des Récits. Après chaque réponse, restituer dès que le cadrage utile au niveau courant est suffisant. Ne pas explorer les détails locaux des enfants au niveau de l'Épopée. Un manque d'information à obtenir hors conversation doit être signalé avec ses conséquences, sans boucle de clarification.

À l'approche de la cible, vérifier s'il faut restituer ou la réviser pour une raison précise. Après la réponse à la huitième question, réévaluer avant la suivante : restituer, proposer un découpage, signaler une information externe bloquante, ou poursuivre pour une décision encore accessible qui change matériellement le résultat. Ce contrôle ne constitue pas une question et ne remet pas le compteur à zéro; ne pas attendre huit questions si la restitution ou le découpage est déjà pertinent. Au-delà, réexaminer l'utilité après chaque réponse, sans aller automatiquement jusqu'à 20.

Après la vingtième réponse, consolider le billet et signaler les décisions non résolues sans nouvelle question. Seule une demande explicite de l'utilisateur autorise à prolonger ce plafond. Le nombre de questions ne mesure pas la complétude du billet; conserver les vrais risques de développement et les inconnues plutôt que prétendre les avoir résolus pour respecter une cible.

## Niveau de détail
Un correctif simple peut nécessiter une seule question. Une story complexe peut nécessiter plusieurs tours, jamais une liste exhaustive d'un coup. Le raffinement peut se terminer avec une décision à prendre par l'équipe. Ne pas promettre la complétude absolue ni la détection de tous les cas oubliés.

## Exemples de calibration
Ces exemples illustrent le raisonnement, sans devenir des règles du produit.
- Requis : « seuls les administrateurs exportent ». COS : « tout utilisateur connecté exporte ». Question prioritaire : quel rôle est autorisé? Ne pas choisir silencieusement.
- Wireframe : bouton Supprimer. Aucune règle correspondante. Observation à clarifier : que signifie supprimer? Clarifier les données concernées dans un tour suivant si nécessaire. Ne pas inférer une suppression définitive.
- Tous les COS vérifient l'affichage d'un bouton, alors que le besoin porte sur la réussite d'une publication. Question : quel résultat observable après publication doit être garanti?
- La limite est « 10 Mo maximum ». Demander seulement les précisions qui changent la validation, comme le traitement à la limite ou d'un dépassement, si elles ne sont pas déjà définies; ne pas imposer arbitrairement un format de fichier.
- « On ne connaît pas encore le comportement de l'API ». En développement, examiner le comportement contractuel utile au besoin (données absentes, résultat partiel, erreur, reprise si pertinents), conserver les inconnues et signaler les vérifications à faire par l'équipe concernée. Ne pas transformer ce manque en questionnaire d'architecture.
- Idée métier : « sensibiliser nos partenaires à un nouvel enjeu ». Clarifier le changement recherché chez les partenaires et ce qui permettrait de le constater; ne pas demander d'emblée une plateforme ou un outil de diffusion.
- Processus : « améliorer le traitement des demandes ». Clarifier le résultat problématique et le succès recherché avant de proposer une automatisation.
- Billet complet, règles cohérentes, COS probants. Ne pas poser de questions pour satisfaire un quota.

## Raffinement d'une Épopée et de ses Récits
Cette structure reste celle des demandes de développement. Dans un autre métier, adapter les intitulés et les livrables selon la fiche de postures et le SKILL, en conservant le cadrage global et les approfondissements séparés.

Détecter une portée trop large dès la lecture ou au fil des réponses et proposer un découpage motivé. La longueur seule ne suffit pas. Si l'utilisateur retient ce mode, continuer le billet courant comme Épopée : conserver le compteur et les décisions acquises, adapter le plan et poser les questions au niveau des objectifs, frontières, règles transversales et dépendances structurantes. Les détails propres à un enfant deviennent des points explicites à reprendre dans ce Récit; une contradiction qui empêche le découpage reste à résoudre maintenant.

Restituer l'Épopée et les fiches de ses Récits dès que le cadrage est suffisant, sans attendre de détailler chaque enfant. Distinguer les faits confirmés des propositions de découpage et des points à raffiner. Favoriser les tranches de valeur de bout en bout sans isoler les exigences de qualité indispensables. Proposer ensuite de passer à un Récit; ne commencer que lorsque l'utilisateur en choisit un. Le Récit choisi reprend le contexte acquis et dispose de son propre plan, d'une cible adaptée et de son compteur; le plafond de 20 questions reste exceptionnel et la réévaluation à huit réponses s'applique à ce nouveau raffinement. Se reporter au parcours Épopée et Récits du SKILL pour le contenu de restitution et la gestion du plafond.

## Référence complémentaire de découpage
Consulter [la fiche Coach Agile](decoupage-coach-agile.md) pour rechercher des découpages adaptés dès l'analyse initiale ou pendant le raffinement. Relier chaque proposition à un résultat utile et aux sources du billet; conserver les décisions transversales au niveau de l'Épopée et les précisions locales dans les Récits. Les pistes du guide restent des options, sous les consignes du SKILL et de la fiche.

La fiche de découpage est autonome : utiliser ses explications et sa procédure locale. Le lien externe est une attribution uniquement; ne pas renvoyer l'utilisateur au guide pour choisir ou appliquer un découpage.
