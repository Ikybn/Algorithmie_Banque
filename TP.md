# TP OF (Organisme de Formation)

Prépavenir a besoin d'un système de gestion pour les demandes d'inscription aux formations du catalogue.

### Le catalogue

-Développeur Web et Web mobile (niveau bac)
-Concepteur Développeur d'Applications (niveau bac)
-Web designer 
-Référencement SEO 

Le programme sera utilisé par 2 personnes (un admin et un assistant), l'objectif étant de faciliter la gestion du processus d'inscription des futurs élèves.

--- contact@prepavenir.fr

Prise de notes : 

Martin se rend sur le site web prepavenir afin de s'inscrire à une formation de leur catalogue.
Il clique sur l'onglet 'Inscription' de la navigation.

Le processus d'inscription est lancé dans un formulaire.
Martin renseigne son -nom
                     -prénom 
                     -adress email
                     -téléphone 
                     -cv
                     -coche la formation choisie avec un roulement des dates de session disponibles 
SI 
Martin ne renseigne pas tout ses éléments. 
ALORS 
La candidature n'est pas valide.
SINON SI 
Martin ne rempli pas une des cases. Elle affiche un message 'tous les champs doivent être renseigner'.
SINON 
L'inscription de Martin est valide.
Le processus d'inscription est valide.

La candidature possède un numéro qui est incrémenté de 1 à chaque nouvelle inscription.
La demande d'inscription est envoyé à contact@prepavenir.fr
L'admin et l'assistant reçoivent un mail de notification d'inscription à une formation.

L'administrateur gère les candidatures dans ses fichiers admin.
SI
Le candidat n'est pas retenue 
ALORS 
L'admin peut supprimer le candidat dans son fichier de sauvegarde.
SINON SI 
Le candidat change de formation. L'admin peut modifier le dossier du candidat. 
SINON 
La candidature est retenue. 
Elle reste dans le fichier admin de prepavenir.


