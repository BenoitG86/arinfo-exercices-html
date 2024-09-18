# Instructions :

### Créer une nouvelle page HTML :

- Créez un nouveau fichier HTML sur votre ordinateur appelé formulaire.html.

- Ajoutez les balises de base pour définir la structure d'une page HTML (doctype, head, body).

- Ajoutez un titre à votre page :

-  Dans la balise head, insérez un titre pour la page.

### Créez le formulaire :

- Dans la balise body, ajoutez un titre de niveau 1 pour décrire le formulaire.

- Créez une balise form avec les attributs action="" et method="post". (Cela ne soumet pas encore les données, mais vous allez structurer le formulaire.)

- Insérez une balise fieldset pour regrouper les éléments du formulaire.

- Ajoutez un titre de section avec legend, par exemple : "Formulaire de test".

### Ajoutez des éléments de formulaire :

- Ajoutez une liste non ordonnée pour structurer les différents éléments du formulaire.

- À l'intérieur de cette liste, créez différents champs de formulaire (input), comme décrit ci-dessous :

a) Boutons radio pour sélectionner la civilité :
Utilisez des boutons radio ( type="radio") pour permettre à l'utilisateur de choisir entre "Monsieur" et "Madame".
Utilisez un label pour chaque option.

b) Champs de texte :
Créez des champs de texte pour recueillir le nom, prénom, numéro de téléphone et email de l'utilisateur. Utilisez le bon type d'input (text, tel, email). Les champs importants doivent être requis.
Assurez-vous d'associer correctement chaque champ avec son label en utilisant l'attribut « for ».

c) Liste déroulante pour le département :
Ajoutez une liste déroulante pour permettre à l'utilisateur de sélectionner son département parmi plusieurs options avec une option présélectionnée et non sélectionnable par l’utilisateur.

d) Champ de message :

- Ajoutez un champ pour permettre à l'utilisateur de saisir un message. Utilisez un champ de texte étendu.

### Ajoutez des boutons de soumission et de réinitialisation :
- Ajoutez un bouton de soumission (type="submit") pour permettre à l'utilisateur d'envoyer le formulaire.
- Ajoutez un bouton de réinitialisation (type="reset") pour vider tous les champs du formulaire.