# Découper une demande en Récits — fiche autonome

Cette fiche contient les repères nécessaires à son utilisation dans le plugin. Aucun accès au Web ni lecture de l'article source n'est nécessaire. Les pistes sont des possibilités à évaluer, jamais une liste à appliquer intégralement.

## Treize pistes de découpage
1. **Intentions combinées** : repérer les demandes reliées par « et » ou « ou »; examiner leur séparation.
2. **Résultats des COS** : distinguer des capacités autonomes derrière plusieurs critères.
3. **Parcours** : examiner les étapes; conserver un chemin utile.
4. **Scénarios** : séparer les alternatives selon leur valeur et leur risque.
5. **Actions** : distinguer création, lecture, modification et suppression lorsque chacune répond à un besoin.
6. **Données** : limiter d'abord les catégories ou formats traités.
7. **Règles métier** : différencier les variantes et les conditions applicables.
8. **Supports et interactions** : examiner appareils, interfaces et modes de saisie.
9. **Rôles** : isoler les résultats propres aux différents bénéficiaires.
10. **Objectifs de qualité** : prévoir des améliorations progressives à partir d'un minimum acceptable.
11. **Complexité** : commencer par un cas simple, puis ajouter des contraintes.
12. **Socle commun** : porter l'effort initial dans une première capacité, puis ajouter ses variantes.
13. **Apprentissage** : séparer une exploration nécessaire de la réalisation connue.

## Consignes propres au plugin
Ces consignes adaptent la référence au fonctionnement existant du plugin :
- Consulter cette fiche dès la première analyse si la portée paraît large, et lorsque le découpage devient pertinent ensuite.
- Retenir seulement les angles adaptés au besoin; expliquer la valeur et les frontières de chaque Récit proposé. Comparer brièvement plusieurs découpages uniquement si cela aide une décision réelle.
- Ne pas convertir mécaniquement chaque COS, étape, rôle ou conjonction en Récit. Un indice appelle un examen, pas une séparation automatique.
- Ne pas utiliser un nombre de COS ou de points comme seuil universel. Ne pas conclure à une Épopée sur ces seuls indices.
- Respecter les contraintes confirmées de sécurité, d'accessibilité, d'intégrité et de qualité. Leur report exige un arbitrage explicite compatible avec ces contraintes; une tranche doit rester utilisable et cohérente.
- Repérer les préalables et dépendances déjà connus, qu'ils concernent des personnes, des activités, des informations ou un système. Pour un besoin logiciel, ne pas transformer un socle supposé en prescription d'architecture ou en découpage par couche. Distinguer une exploration d'un Récit de réalisation et préciser la décision qu'elle doit éclairer.
- Le parcours Épopée et Récits du SKILL reste applicable : proposer le découpage, attendre le choix, poursuivre au niveau approprié, conserver les questions locales pour les enfants et livrer dès que le cadrage est suffisant.


## Adapter les pistes au domaine
En développement, conserver le découpage fonctionnel en Épopée et Récits et la vérification des règles, dépendances et COS. Hors développement, appliquer [la posture métier pertinente](postures.md) et proposer des volets par résultat utile si nécessaire, sans transformer chaque demande en backlog logiciel.

Les pistes ci-dessus ne supposent pas que la demande soit logicielle. Pour un besoin métier, raisonner en résultats, activités, publics, règles et dépendances du domaine. Ignorer les pistes liées aux interfaces ou aux données si elles ne sont pas pertinentes. Le socle commun désigne les préalables connus, pas une architecture à concevoir. Un Récit peut décrire un résultat métier sans fonctionnalité numérique. Ne pas inventer de solution pour remplir une catégorie de découpage.

## Application autonome pendant le raffinement
Les instructions suivantes sont propres au plugin et complètent les pistes ci-dessus.

### Première analyse
Identifier le résultat global et les résultats distincts effectivement présents dans les sources. Une demande peut justifier une Épopée dès cette lecture. Présenter alors une raison concrète et une première répartition en Récits; ne pas attendre d'avoir détaillé chaque comportement. Ne pas estimer la taille au nom de l'équipe.

### Choisir un découpage
Examiner silencieusement les pistes pertinentes. Pour chaque frontière envisagée, vérifier :
- Quel résultat observable ce Récit apporte-t-il?
- Quelles règles sont communes à l'ensemble et lesquelles lui appartiennent?
- Dépend-il d'un autre Récit, et pourquoi?
- Quelles informations sont confirmées, proposées ou encore inconnues?
- Quels détails peuvent attendre son propre raffinement sans empêcher le cadrage global?

Écarter les séparations qui n'apportent qu'un fragment technique inutilisable ou masquent une dépendance essentielle. Ne pas prétendre rendre tous les enfants indépendants : documenter les dépendances réelles. Si plusieurs options sont plausibles, proposer celle qui correspond le mieux au résultat recherché et expliquer brièvement l'arbitrage.

### Poursuivre au bon niveau
Après acceptation du découpage, garder le billet courant comme Épopée. Clarifier les objectifs, frontières et règles transversales. Pour un détail local, enregistrer le Récit concerné et la question à reprendre, puis revenir au cadrage global. Ne pas questionner tous les enfants dans la conversation de l'Épopée. Conserver le compteur déjà engagé et adapter la cible aux seules décisions de cadrage global restantes. Livrer sans attendre cette cible si le résultat est utile. Si huit réponses ont été atteintes, appliquer la réévaluation du SKILL sans attendre d'approfondir les enfants.

### Restituer
Dès qu'une synthèse utile est possible, fournir l'Épopée et ses Récits avec les éléments confirmés, leurs limites et les points à approfondir. Proposer ensuite de choisir un Récit. Son raffinement commencera sur demande, avec une cible adaptée, son propre compteur et le contexte déjà acquis; 20 reste un plafond exceptionnel. Le SKILL définit le format complet et le plafond de questions.

## Attribution
Repères de découpage synthétisés et reformulés à partir de Jean-Christophe Pagès, Coach Agile, 10 juillet 2022.
[Article source](https://coach-agile.com/2022/07/le-guide-ultime-et-pratique-zero-bullshit-pour-decouper-tes-user-stories/) — consulté le 23 octobre 2026.
Ce lien documente la provenance; il ne constitue pas une étape du workflow. Le texte intégral, les illustrations et les exemples de l'article ne sont pas reproduits.
