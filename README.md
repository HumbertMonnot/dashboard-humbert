# Dashboard-humbert

Application personnelle, à un seul utilisateur.

Un outil privé qu'une personne a construit pour elle-même. Il réunit ses propres mesures de sommeil, de récupération et d'entraînement avec son agenda et sa liste de tâches, dans un résumé quotidien.

- [Présentation](#presentation)
- [Politique de confidentialité](#confidentialite)
- [Conditions d'utilisation](#conditions)

<a name="presentation"></a>
## Présentation

Dashboard-humbert est exploité par son propriétaire, pour lui seul. Il n'a aucun autre utilisateur, n'est pas proposé au public et n'est pas un service commercial. Personne ne peut s'y inscrire.

Il lit les données de son propriétaire dans les services qu'il utilise, en lecture seule, et en tire un court résumé quotidien et des réponses à ses propres questions : comment il a dormi, ou si la journée se prête à une séance intense.

### Ce qu'il lit chez Oura

| Type de données Oura | Accès | Usage |
|---|---|---|
| Daily (sommeil, forme, activité) | Lecture | La dernière nuit, la récupération et la tendance des dernières semaines |
| Workout | Lecture | Les séances détectées par la bague |
| SpO2 | Lecture | La moyenne d'oxygénation de la nuit |
| Stress | Lecture | Le bilan de stress et de récupération de la journée |
| Email, Personal | Non demandé | |
| Heartrate, Tag, Session, Ring configuration, Heart health | Non demandé | |

L'application n'écrit jamais rien chez Oura.

<a name="confidentialite"></a>
## Politique de confidentialité

Dernière mise à jour : 19 novembre 2026

### Qui est concerné

Une seule personne : le propriétaire, qui est aussi l'exploitant et l'unique utilisateur. L'application ne collecte aucune donnée sur qui que ce soit d'autre.

### Données consultées

Les types de données Oura listés plus haut, lus par l'API d'Oura après que le propriétaire a autorisé l'application depuis son propre compte Oura. L'accès est en lecture seule et limité aux types qu'il a cochés.

### Usage des données

Uniquement pour produire le résumé quotidien du propriétaire et répondre à ses propres questions sur son sommeil, sa récupération et son entraînement.

Ces textes sont rédigés par le logiciel d'assistant personnel du propriétaire, qui s'appuie sur un modèle de langage (IA) exploité par un prestataire tiers. Quand un résumé ou une réponse est produit, les mesures nécessaires sont transmises à ce prestataire pour que le texte soit généré.

- L'application n'utilise pas ces données pour entraîner ou ajuster un modèle.
- Elles ne sont ni vendues, ni utilisées à des fins publicitaires, ni croisées avec des données d'autres personnes.

### Conservation

- Les identifiants d'accès sont conservés sur un serveur privé contrôlé par le propriétaire, lisibles par le seul compte de l'application.
- Les mesures Oura sont relues au moment où un résumé est nécessaire. L'application n'en tient pas de base séparée.
- Les résumés et les réponses envoyés au propriétaire, qui peuvent citer des mesures, restent dans son historique de messages privé et dans ses sauvegardes pendant 24 mois au plus.

### Destinataires

Personne d'autre que le propriétaire, en dehors des prestataires nécessaires au fonctionnement de l'outil pour lui : le prestataire d'IA décrit plus haut, l'hébergeur du serveur privé et le service de messagerie qui lui remet le résumé.

### Contrôle et suppression

Le propriétaire peut retirer l'autorisation à tout moment depuis son compte Oura, ou supprimer les identifiants du serveur. Supprimer son historique de messages supprime les résumés.

### Contact

L'adresse de contact enregistrée avec cette application chez Oura.

<a name="conditions"></a>
## Conditions d'utilisation

Dernière mise à jour : 19 novembre 2026

### Usage strictement personnel

Dashboard-humbert n'est utilisé que par son propriétaire. Aucun compte n'est créé pour d'autres personnes, et personne d'autre n'a accès à l'outil ni à ses données.

### Projet indépendant

C'est un projet personnel indépendant. Il n'est ni affilié à Oura ou aux autres services qu'il consulte, ni approuvé ou soutenu par eux. Leurs noms et leurs marques appartiennent à leurs propriétaires.

### Pas un avis médical

Les résumés sont donnés à titre d'information. L'application n'est pas un dispositif médical et ne pose aucun diagnostic. Les décisions de santé reviennent au propriétaire et, au besoin, à un médecin.

### Sans garantie

L'application est fournie en l'état. Ses résumés peuvent être incomplets, tardifs ou faux, et elle cesse de fonctionner quand un service dont elle dépend est indisponible ou retire son accès.

### Services tiers

Les données lues dans un service tiers restent soumises aux conditions de ce service. Le propriétaire est responsable de l'usage qu'il en fait.

### Arrêt

Le propriétaire peut arrêter à tout moment, en retirant l'autorisation dans le compte concerné et en supprimant les identifiants du serveur.
