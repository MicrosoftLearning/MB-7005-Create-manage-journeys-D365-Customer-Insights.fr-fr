---
lab:
  title: "Labo\_3\_: créer un parcours basé sur des segments"
---
## Labo 3 : créer un parcours basé sur des segments 

Dans ce labo, vous allez apprendre à effectuer les opérations suivantes :
- Créer un parcours basé sur des segments 
- Définir des critères de sortie pour le segment 

### Tâche 1 : créer un parcours basé sur des segments 
Contoso souhaite être en mesure d’interagir avec des clients qui répondent à des critères démographiques spécifiques. Pour ce faire, l’entreprise crée un parcours basé sur des segments.

1. Dans Engagement, sélectionnez **Parcours**.

1. Dans la barre de commandes, cliquez sur **+ Nouveau parcours**.

1. Sélectionnez **Ignorer et créer entièrement**.

1. Dans Nom du parcours, entrez **Campagne Seattle**.

1. Dans Choisir le type de parcours, sélectionnez **Basé sur un segment**.

1. Dans Sélectionner un segment, choisissez **Clients Seattle**.

1. Dans Sélectionner la fréquence, choisissez **Un parcours répétitif dans lequel tous les membres de l’audience répètent le parcours :**

1. Sélectionnez **6 semaines**.

1. Définissez le fuseau horaire sur le vôtre.

1. Définissez la date de début sur la date du jour, et l’heure à 30 minutes de l’heure actuelle.

1. Définissez la date de fin sur environ six mois à partir d’aujourd’hui.

1. Cliquez sur **Créer**.

1. Dans les paramètres du parcours à droite, vérifiez que la section **Entrée** est sélectionnée.

1. Accédez à l’option **Exclure par segments** et sélectionnez **Clients professionnels**.

### Tâche 2 : définir les critères de sortie du parcours
Étant donné que l’objectif de ce parcours est d’inciter les gens à s’inscrire à un événement marketing, nous voulons nous assurer qu’une fois qu’ils s’inscrivent, quel que soit l’endroit où ils se trouvent dans le parcours, le parcours se termine pour eux.  En outre, si des employés de Contoso vivent à Seattle, nous voulons qu’ils soient au courant de l’événement à venir. Cependant, nous ne voulons pas qu’ils entrent dans le parcours. Pour cette raison, nous allons limiter l’accès au parcours.  

1.  Sélectionnez la section **Quitter**.  

1.  Ensuite, dans **Quitter lorsqu’un déclencheur se produit**, recherchez **Inscription à l’événement marketing créée**.

1.  Sélectionnez **Ajouter une condition**.

1.  Développez **Inscription à l’événement marketing créée**, puis **Référence sur l’événement marketing**.

1.  Sélectionnez **Événement**.

    ![Capture d’écran d’une liste de critères de sortie avec l’événement sélectionné.](../Labs/Media/exit-criteria.png)

1.  Définissez l’opérateur sur **Est égal à**.

1.  Définissez la valeur sur **Ted Contoso**.

1. Dans **Quitter by segments**, définissez la valeur sur **Clients Contoso**. 

### Tâche 3 : créer le parcours
Maintenant que nous avons défini les différents critères liés à ce parcours, nous allons créer le parcours lui-même.  

1. Dans le concepteur de parcours, cliquez sur l’**icône plus (+)** dans la vignette Contact créé.

1. Sélectionnez **Branche d’attribut (branche basée sur une valeur spécifique)**.

1. Dans Nom d’affichage à droite, nommez l’attribut **Nouveau client professionnel**.

1. Sélectionnez **Branche 1** et dans Choisir un attribut, recherchez **Description (description)** dans **Contact**.

1. Remplacez la valeur Égal à par **Contient**.

1. Dans Valeur, entrez **Entreprise**.

1. Cliquez sur l’**icône plus (+)** sous Branche 1.

1. Sélectionnez **E-mail : envoyer un e-mail**.

1. Dans Sélectionner un e-mail, choisissez **E-mail de bienvenue 1**.

1. Cliquez sur l’**icône plus (+)** sous la vignette Envoyer un e-mail.

1. Sélectionnez **Attendre le déclencheur**.

1. Dans le panneau de la branche If/then à droite, dans Attendre, Choisir un type de condition de branche, sélectionnez **Le message précédent obtient une interaction**.

1. Dans Choisir une interaction, sélectionnez **Lien d’e-mail cliqué**.

1. Dans **Quelle est la limite de temps ?**, entrez 10 minutes.

1. De retour dans le diagramme Parcours, pour spécifier le lien cliqué, sélectionnez **Créer des branches**.

1. Sélectionnez l’attribut **Lien d’e-mail cliqué**.

1. Dans la branche 1, choisissez un lien, sélectionnez le bouton d’appel à l’action dans l’e-mail.

1. Sous le bouton, cliquez sur le chemin d’accès, cliquez sur l’icône **plus (+)**.

1. Sélectionnez **Envoyer un message électronique**.

1. Dans Sélectionner un e-mail, choisissez **E-mail de bienvenue 2**.

1. Dans le chemin Non correspondant, cliquez sur l’**icône plus (+)**.

1. Sélectionnez **Envoyer un message électronique**.

1. Dans Sélectionner un e-mail, choisissez **E-mail de bienvenue 3**.

1. Enregistrez le parcours.

1. Passez en revue le parcours. Apportez les modifications finales.

1. Cliquez sur **Publier**. Attendez que le parcours soit publié.

