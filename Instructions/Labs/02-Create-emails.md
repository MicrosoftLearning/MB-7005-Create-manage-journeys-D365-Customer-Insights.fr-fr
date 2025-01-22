---
lab:
  title: "Labo\_1\_: créer des e-mails"
---

## Labo 1 : créer des e-mails 

Dans ce labo, vous allez apprendre à effectuer les opérations suivantes :
- Créer des e-mails à utiliser dans un parcours
- Utiliser des ressources chargées dans un e-mail
- Vérifier le contenu de votre e-mail et l’envoyer

### Tâche 1 : créer votre premier e-mail
1. Connectez-vous à Dynamics 365 Customer Insights - Journeys.

1. Accédez à la zone de travail **Parcours en temps réel**.

1. Dans Canaux, sélectionnez **E-mails**.

1. Créez l’e-mail.
   - Cliquez sur **+Nouveau** pour créer un e-mail.
   - Dans la galerie de modèles, sélectionnez **Ignorer**.

1. Entrez des détails sur l’e-mail.
   - Nom : e-mail de bienvenue 1
   - Objet : bienvenue chez Contoso Insurance
   - Texte de la préversion : nous nous engageons à vous fournir une assurance qualité.

1. Sélectionnez le profil de marque par défaut comme profil de marque.

1. Accédez à **Paramètres** et développez **Conformité**. Vérifiez que l’objectif est défini sur **Commercial**.

1. Concevez l’e-mail. Reportez-vous à la capture d’écran de l’e-mail de bienvenue 1 ci-dessous pour connaître les idées de conception et de contenu, à l’aide de l’image Hero que vous avez chargée dans les instructions de configuration. Vous pouvez modifier les images et le contenu comme vous le souhaitez, mais vous devez inclure un bouton d’appel à action dans cet e-mail, car il sera utilisé comme critères d’embranchement dans le parcours.

![Capture d’écran de l’e-mail de bienvenue 1.](../Labs/Media/welcome-email-1-example.png) 

1. Voici un exemple de copie pour cet e-mail. Vous pouvez copier et coller ceci dans votre conception d’e-mail. Utilisez la **personnalisation** afin d’entrer du contenu dynamique pour le prénom du contact. 

    ```
    {{FirstName}},
    
    Thank you for putting your trust in Contoso Insurance. We're honored to have you as a customer and look forward to building a lasting relationship with you. 
 
    As America's \#1 insurance company, we're committed to providing quality insurance that protects all aspects of your business. 
 
    We've put together a welcome kit that provides insight about our agency, advises on what to do if you need to report a claim, and provides our staff's direct contact information. Use the link below to download it. 
 
    Feel free to contact us any time at 888-888-8888 with any questions you have. And don't forget to download our mobile app where you can view your account history, pay your bill, and more. 
    ```

1. Ajoutez un bouton à l’e-mail 

    - Dans la boîte à outils, sélectionnez l’onglet **Éléments**. 
    - Faites glisser un bouton sous le texte principal. 
    - Modifiez l’URL en contoso.com. 
    - Développez la section Style. 
    - Remplacez la couleur du bouton par #0076ad. 

1.  Prévisualisez, testez et envoyez votre e-mail. 

    - Accédez à l’onglet **Prévisualiser et tester** de votre e-mail pour vérifier votre e-mail. 
    - Utilisez l’**envoi de test** pour vous envoyer une copie. Entrez votre adresse e-mail personnelle. Sélectionnez le contact que vous avez créé précédemment : la personnalisation renseigne le prénom de ce contact. Vérifiez vos dossiers de courrier indésirable si cet e-mail ne figure pas dans votre boîte de réception. 
    - Apportez les modifications finales. 
    - Cliquez sur **Vérifier le contenu**. Corrigez les erreurs si nécessaire. 
    - Cliquez sur **Prêt à envoyer**. 

### Tâche 2 : créer votre deuxième e-mail
Nous allons créer deux e-mails supplémentaires en copiant l’e-mail que vous venez de créer.

1. Lorsque l’e-mail de bienvenue 1 est ouvert, cliquez sur la liste déroulante en regard d’**Enregistrer**, puis sélectionnez **Enregistrer sous**.

1. Remplacez le nom de l’e-mail par **E-mail de bienvenue 2** 

1. Cliquez sur **Enregistrer et fermer**.

1. Sélectionnez **Afficher l’enregistrement** dans la fenêtre contextuelle pour accéder à votre e-mail nouvellement créé. (S’il ne s’affiche pas, accédez à **E-mails** et sélectionnez **E-mail de bienvenue 2**.)

1. Modifiez l’objet et le texte d’aperçu.
    - **Objet** suggéré : obtenez un accès à la demande à votre portail Contoso Insurance.
    - **Texte d’aperçu** suggéré : passez en revue les informations sur le compte, les détails de la police, envoyez une réclamation, etc.

1. Concevez l’e-mail. Reportez-vous à la capture d’écran de l’e-mail de bienvenue 2 ci-dessous pour connaître les idées de conception et de contenu. Vous pouvez modifier les images et le contenu comme vous le souhaitez. 

![Capture d’écran de l’e-mail de bienvenue 2.](../Labs/Media/welcome-email-2-example.png) 

1. Voici un exemple de copie pour cet e-mail. Vous pouvez copier et coller ceci dans votre conception d’e-mail. (Note : nous vous recommandons de laisser le prénom du premier e-mail, puis de remplacer le reste de la copie par ceci.) 

    ```
    I would like to welcome you to the Contoso family! Our specialists are here to help you with all your insurance needs. We also encourage you to setup your Contoso Insurance online account to gain 24/7 access to:  
        -   Your account information and policy details. 
        -   Submit a request for coverage verification, start a claim, or review prior claims. 
        -   A secure and encrypted internal messaging tool for sharing sensitive information. 
    Feel free to contact me with any questions you have. 
        
    Cheers, 
    John Smith, Insurance Specialist   jsmith@contosoinsurance.com 
    888-888-8888 

1. Preview, test, and go live with your email.

### Task 3: Create your third email
We will create one final email by copying email 2.

1. Create a new email by copying email 2. Name the email Welcome email 3. 

1. Enter details about the email.
    - Suggested **Subject:** Welcome to Contoso
    - Suggested **Preview text:** Review your welcome information.

1. Design the email. Refer to the screenshot of Welcome Email 3 below for design and content ideas. You can modify the images and content as desired. 

![Screenshot of Welcome Email 3.](../Labs/Media/welcome-email-3-example.png) 

1. Here is sample copy for this email. You can copy and paste this into your email design. (Note: We recommend leaving FirstName from the first email and then replacing the rest of the copy with this.) 

    ```
    Merci d’avoir fait confiance à Contoso Insurance. Je suis honoré de vous compter parmi nos clients et j’ai hâte de construire avec vous une relation durable. Votre kit de bienvenue fournit des informations sur notre agence, vous conseille sur ce que vous devez faire si vous devez signaler une réclamation et fournit les coordonnées directes de notre équipe. 

    Utilisez le lien ci-dessous pour télécharger le kit à partir de notre site web.
    
    N’hésitez pas à me contacter si vous avez des questions. Cordialement, John Smith, Conseiller en assurances   jsmith@contosoinsurance.com 888-888-8888 

1. Mettez à jour le bouton dans l’e-mail. Dans le champ **Texte de bouton**, remplacez-le par **Cliquez ici pour obtenir le kit de bienvenue**.

1. Prévisualisez, testez et envoyez votre e-mail.
