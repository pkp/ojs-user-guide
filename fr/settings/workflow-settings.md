# Paramètres du flux des travaux

1. [Soumission](workflow-settings#submission)
1. [Évaluation](workflow-settings#review)
1. [Bibliothèque de l'éditeur](workflow-settings#publisher)
1. [Courriels](workflow-settings#emails)

Cet onglet permet de configurer tous les aspects du [flux des travaux](../editorial-workflow), incluant la gestion des fichiers, les directives de soumission, les directives et dates butoirs d'évaluation, les courriels de notifications, et plus encore. Pour plus d'informations, veuillez consulter [Learning OJS 3 Workflow Settings](https://docs.pkp.sfu.ca/learning-ojs/en/settings-workflow) (en anglais).

## <a name="submission"></a>Soumission
L'onglet Soumission permet de déterminer les éléments que les auteurs-es doivent fournir ou approuver lorsqu'ils font une soumission.

### Métadonnées
Si vous activez un champ de métadonnée, il sera disponible pour chaque soumission. Lorsque vous cochez une métadonnée, vous permettez aux auteur-trices de l'ajouter au moment de faire une soumission. Autrement, seul-e un-e éditeur-trice pourra ajouter cette métadonnée.

### Éléments
Les éléments définissent les types de documents pouvant être inclus avec une soumission. Vous pouvez ajouter de nouveaux éléments, ou bien modifier ou supprimer les éléments par défaut. Les éléments peuvent être configurés afin d'être complémentaires ou dépendants, ce qui détermine s'ils doivent être publiés ou non, et de quelle manière.

### Liste de vérification
Cet onglet permet de configurer la liste des vérifications que les auteurs-es doivent compléter avant de créer une soumission. Il s'agit d'un bon endroit pour indiquer les directives relatives aux références, à la taille de police de caractère, à l'interligne, au format de fichier, etc.

### Directives aux auteurs-es
Ces directives seront affichées aux auteurs-es au moment de la soumission.

## <a name="review"></a>Évaluation
Cet onglet permet de configurer vos politiques et procédures de révision, incluant les dates butoirs, les notifications, les directives aux évaluateurs-trices, etc.

### Configuration
Sélectionnez le mode d'évaluation par défaut du système. Les éditeurs-trices peuvent modifier le mode d'évaluation à la pièce pour les soumissions et les évaluations.
- L'**évaluation en double aveugle** empêche l'évaluateur-trice et l'auteur-e de connnaître leur identité respective.
- L'**évaluation en simple aveugle** empêche l'auteur-e de connaître l'identité de l'évaluateur-trice.
- L'**évaluation ouverte** permet aux évaluateur-trices et auteur-es de connaître leur identité respective.

Si vous choisissez l'option **Activer l'accès en un clic pour l'évaluateur-trice**, le courriel d'invitation aux évaluateurs-trices contiendra l'URL d'une page d'évaluation de soumission sans exiger de connexion. Pour des raisons de sécurité, lorsque cette option est activée, les éditeurs-trices ne pourront ni modifier, ni ajouter de destinataires (c.c. ou c.c.i.) avant d'envoyer l'invitation aux évaluateurs-trices.

### Conseils aux évaluateurs-trices
Cet onglet permet de fournir des critères afin d'évaluer l'admissibilité d'une soumission à la publication dans une revue, voire des instructions pour préparer une évaluation utile et efficace. Les évaluateurs-trices auront également la chance de fournir des commentaires destinés aux auteurs-es et aux éditeurs-trices, ainsi que des commentaires destinés uniquement aux éditeurs-trices.

### Formulaires d'évaluation
Si désiré, vous pouvez concevoir des formulaires afin de demander des informations spécifiques à vos évaluateurs-trices. Un-e éditeur-trice peut sélectionner un formulaire au moment d'assigner un-e évaluateur-trice, et l'évaluateur-trice devra compléter ce formulaire au moment de soumettre l'évaluation.

## <a name="publisher"></a>Bibliothèque de l'éditeur 
La bibliothèque de l'éditeur est un dépôt permettant de conserver et partage rapidement les fichiers communs, tels que les directives de rédaction, les contrats de publication et documents d'autorisation, ainsi que le matériel de marketing.

Les éléments stockés dans la bibliothèque de l'éditeur peuvent être rapidement incorporés à la [bibliothèque d'une soumission](../editorial-workflow#submission-library) afin d'être partagés avec les auteurs-es ou les assistants-es.

## <a name="emails"></a>Courriels
OJS envoie plusieurs courriels au cours des diverses étapes du [flux des travaux](../editorial-workflow) ou à l'occasion d'autres procédures, telles que l'enregistrement d'un utilisateur-trice ou l'accusé de réception d'une soumission. Les paramètres de cet onglet permettent de modifier la signature jointe à chaque courriel, ainsi que de changer les messages par défaut envoyés pour chaque type de courriel.

Vous pouvez consulter et modifier le contenu de chaque courriel en cliquant sur la flèche située à sa droite.
