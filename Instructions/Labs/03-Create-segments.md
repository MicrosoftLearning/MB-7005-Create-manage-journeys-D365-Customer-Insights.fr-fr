---
lab:
  title: "Labo\_2\_: créer des segments"
---

## Labo 2 : créer des segments 

Dans ce labo, vous allez apprendre à effectuer les opérations suivantes :
- Mettre à jour les informations sur les enregistrements des clients
- Créer un segment 

### Tâche 1 : mettre à jour la ville pour différents clients

L’un des parcours ciblera les clients qui vivent dans une ville spécifique. Pour vous assurer d’avoir des membres dans ce segment, nous devons ajouter une ville à chacun des contacts qui existent actuellement.

1. Connectez-vous à **Dynamics 365 Customer Insights - Journeys**. Assurez-vous d’être dans la zone **Parcours en temps réel**.

1. Dans Audience, sélectionnez **Contacts.**

1. Sélectionnez les 10 premiers contacts dans la liste. 

1. Dans la barre de commandes, sélectionnez **Modifier**.

1. Dans le champ Adresse 1 : ville, entrez **Seattle**.

1. Sélectionnez le bouton **Enregistrer**.

1. Sélectionnez les 50 contacts suivants dans la liste.

1. Dans la barre de commandes, sélectionnez **Modifier**.

1. Dans le champ Adresse 1 : ville, entrez **Portland**.

1. Sélectionnez le bouton **Enregistrer**.

1. Sélectionnez les 10 contacts suivants dans la liste.

1. Dans la barre de commandes, sélectionnez **Modifier**.

1. Dans le champ Adresse 1 : ville, entrez **Boise**.

1. Sélectionnez le bouton **Enregistrer**.

1. Sélectionnez les 10 contacts suivants dans la liste.

1. Dans la barre de commandes, sélectionnez **Modifier**.

1. Dans le champ Adresse 1 : ville, entrez **Seattle**.

1. Basculez vers l’onglet **Détails**. Dans la zone de texte, dans **Notes personnelles**, entrez **Entreprise**.

1. Sélectionnez le bouton **Enregistrer**.

### Tâche 2 : créer un segment pour les clients Humongous Insurance

1. Dans le groupe Audience, accédez à **Segments**.

1. Sélectionnez **+Nouveau segment**.

1. Dans la zone **Nom du segment**, entrez **Humongous Insurance**. Sélectionnez **Contact** comme audience cible. Sélectionnez **Créer**.

1. Sélectionnez **Ajouter un nouveau groupe** dans le concepteur de segments. Tout d’abord, nous allons choisir un **groupe d’attributs**.

1. Dans le volet Attributs, développez **Contact** et sélectionnez **Compte**. Ajoutez l’élément au groupe existant.

1. Dans la recherche du groupe 1, sélectionnez **Humongous Insurance**. La condition du groupe 1 lit « Compte est Humongous Insurance ».

1. Nous voulons ajouter une autre condition au segment. Sélectionnez **+Ajouter** pour ajouter un nouveau groupe et sélectionnez **Groupe d’attributs**.

1. Modifiez l’opérateur sur **ou**.
    - Dans le volet Attribut, commencez à taper **E-mail.** Développez **Contact**. Sélectionnez le bouton **plus** en regard du champ E-mail et ajoutez-le au groupe 2.
    - Créez la condition suivante : **l’e-mail contient humongousinsurance**

1. Cliquez sur **Enregistrer**.

1. Sélectionnez **Prêt à l’emploi** dans la barre d’outils.

1. Sélectionnez l’onglet **Membres et insights**. Vérifiez que vous voyez des contacts avec un e-mail Humongous Insurance ou un nom d’entreprise Humongous. Vous devrez peut-être actualiser ou attendre quelques minutes avant l’apparition des contacts.

### Tâche 3 : créer un segment d’utilisateurs professionnels

1. Dans le groupe Audience, accédez à **Segments**.

1. Sélectionnez **+Nouveau segment**.

1. Nommez le segment **Clients professionnels**. Conservez **Contact** sélectionné en tant qu’audience cible. Sélectionnez **Créer**.

1. Dans le volet **Attributs** , développez **Contact** et sélectionnez **Compte**. Ajoutez l’élément augroupe existant.

1. Dans la recherche du groupe 1, sélectionnez **Contoso, Ltd**.

1. Sélectionnez **Enregistrer**, puis **Prêt à l’emploi**.

1. Attendez que votre segment soit généré.

1. Sélectionnez l’onglet **Membres et insights** pour afficher les membres de votre segment.

### Tâche 4 : créer un segment Contoso  
2.  Dans le groupe Audience, accédez à **Segments**. 

3.  Sélectionnez **+Nouveau segment. **

4.  Nommez le segment **Clients Contoso**. Conservez **Contact** sélectionné en tant qu’audience cible. Sélectionnez **Créer**.

5.  Ajoutez un nouveau groupe et sélectionnez **Créer un groupe d’attributs**. Dans le volet **Attributs**, développez **Contact** et ajoutez **Description** au groupe 1. 

6.  Dans le concepteur de segments, remplacez le qualificateur par **Contains**. Pour la valeur, entrez **Entreprise**.

7.  Sélectionnez **Enregistrer**, puis **Prêt à l’emploi**. 

8.  Attendez que votre segment soit généré. 

9.  Sélectionnez l’onglet **Membres et insights** pour afficher les membres de votre segment. 


### Tâche 5 : créer un segment Clients Seattle
1. Dans le groupe Audience, accédez à Segments.

1. Sélectionnez **+Nouveau segment**.

1. Nommez le segment **Clients Seattle**. Conservez **Contact** sélectionné en tant qu’audience cible.

1. Cliquez sur le bouton **Créer**.

1. Ajoutez un nouveau groupe et sélectionnez **Créer un groupe d’attributs**. Dans le volet Attributs, développez **Contact > Adresse 1**, et ajoutez **Adresse 1 : ville** au groupe 1.

1. Dans le concepteur de segments, laissez le qualificateur tel qu’il est. Pour la valeur, entrez **Seattle**.

1. Sélectionnez **Enregistrer**, puis **Prêt à l’emploi**.

1. Attendez que votre segment soit généré.

1. Sélectionnez l’onglet **Membres et insights** pour afficher les membres de votre segment.
