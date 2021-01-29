# Online-Bank-portal
Description du client des fonctionnalités attendues pour l’application

L’application qui simule un portail de banque en ligne permettant d’effectuer des opérations de création de compte client, validation de la création par un banquier, consultation de compte bancaire, réalisation.

Profils utilisateurs : • Client : Soumet une demande de création de compte pour les nouveaux clients. La création de compte s’effectue à travers un formulaire avec upload d’une pièce d’identité du client. Une fois le compte validé, le client sera en mesure d’effectuer des virements et consulter son compte. Il peut également soumettre une demande de suppression de son compte à travers un formulaire avec upload d’une demande signée. • Banquier : Valide les demandes de création et suppression de compte suite à la consultation des pièces jointes soumises par les clients.

Descriptions des fonctionnalités :

L’application doit avoir deux interfaces distinctes selon le profil de l’utilisateur : une interface client et une interface banquier.

La fonctionnalité de création de compte permet aux utilisateurs de remplir une demande d’ouverture de compte en fournissant les informations suivantes : Nom, prénom, date de naissance, adresse postale, adresse email, mot de passe, et uploader un scan de pièce d’identité. La demande de création est attribuée automatiquement à un des banquiers.

La fonctionnalité d’authentification client permet aux utilisateurs de se connecter sur leurs portails afin de suivre l’état de la demande de création.

La fonctionnalité d’authentification banquier permet aux 5 banquiers (dont les comptes sont prédéfinis sur la base) de se connecter et de valider les demandes de création envoyées par les clients.

Interface authentifiée client :

Si le compte n’est pas encore validé, l’utilisateur ne peut visualiser sur son portail que l’état d’avancement de la demande (en attente de validation, coordonnées du banquier en charge de la validation). Les autres options (ajout d’un bénéficiaire, virement et visualisation de compte et demande de suppression de compte doivent être inaccessibles).

Une fois le compte validé, un identifiant de compte bancaire est automatiquement généré. Le client est alors capable d’ajouter des bénéficiaires, effectuer des virements, visualiser son compte et demander une suppression de compte. L’ajout de bénéficiaire doit aussi être validé par un banquier.

Menu authentifié Banquier : il permet aux banquiers de valider les demandes de création de compte, d’ajout de bénéficiaire et de suppression de compte.
