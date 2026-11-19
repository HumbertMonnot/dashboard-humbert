# Dashboard-humbert

Application personnelle, à un seul utilisateur.

Un tableau de bord privé qu'une personne a construit pour elle-même. Il affiche sur une seule page ses propres mesures de sommeil, de récupération et d'entraînement, à côté de son agenda et de sa liste de tâches.

- [Présentation](#presentation)
- [Politique de confidentialité](#confidentialite)
- [Conditions d'utilisation](#conditions)

<a name="presentation"></a>
## Présentation

Dashboard-humbert est exploité par son propriétaire, pour lui seul. Il n'a aucun autre utilisateur, n'est pas proposé au public et n'est pas un service commercial. Personne ne peut s'y inscrire.

Il lit les données de son propriétaire dans les services qu'il utilise, en lecture seule, et les affiche sur une page que lui seul consulte : sa dernière nuit, ses dernières séances, ses rendez-vous et ses tâches du jour.

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

Uniquement pour les afficher au propriétaire dans son tableau de bord : sa dernière nuit, sa récupération, et quelques moyennes calculées sur les semaines précédentes pour situer la nuit.

Elles ne sont ni vendues, ni utilisées à des fins publicitaires, ni croisées avec des données d'autres personnes.

### Conservation

- Les identifiants d'accès sont conservés sur un serveur privé contrôlé par le propriétaire, lisibles par le seul compte de l'application.
- Les mesures Oura sont relues à chaque affichage du tableau de bord. L'application n'en tient ni base ni historique : chaque page affichée remplace la précédente.

### Destinataires

Personne d'autre que le propriétaire. Le serveur privé qui fabrique la page est loué à un hébergeur.

### Contrôle et suppression

Le propriétaire peut retirer l'autorisation à tout moment depuis son compte Oura, ou supprimer les identifiants du serveur. Il n'y a pas d'autre copie à effacer que la dernière page affichée, sur son ordinateur.

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

Le tableau de bord affiche des mesures à titre d'information. L'application n'est pas un dispositif médical et ne pose aucun diagnostic. Les décisions de santé reviennent au propriétaire et, au besoin, à un médecin.

### Sans garantie

L'application est fournie en l'état. Ce qu'elle affiche peut être incomplet, tardif ou faux, et elle cesse de fonctionner quand un service dont elle dépend est indisponible ou retire son accès.

### Services tiers

Les données lues dans un service tiers restent soumises aux conditions de ce service. Le propriétaire est responsable de l'usage qu'il en fait.

### Arrêt

Le propriétaire peut arrêter à tout moment, en retirant l'autorisation dans le compte concerné et en supprimant les identifiants du serveur.
