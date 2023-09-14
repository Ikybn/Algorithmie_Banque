# Algorithme DAB

Conception d'un algorithme de DAB*, sous forme de pseudo-code.

  *Distributeur Automatique de billets* 

  ---

```text
  Le client insère sa carte dans le distributeur 
  Le processus de vérification de la carte est lancé
    SI la carte n'est pas conforme
      ALORS le distributeur rejette la carte
      Le programme s'arrête
    SINON SI la carte est bloquée
      ALORS le distributeur avale la carte
      Le programme s'arrête
    SINON 
      la carte est valide
      Lancer la demande du code de la carte 
Le distributeur affiche un message "demandant le code de la carte"
Le client tape un code 
    SI le code est incorrect 
        ALORS le distributeur affiche un message "code incorrect"
        ET le compteur de tentative est incrémenté de 1
        SI le compteur de tentative est égale à 3 
            ALORS le distributeur avale la carte
            Le programme s'arrête|
        Lancer la demande du code de la carte
    SINON
      Le code est correct 
      Lancer la demande du montant à retirer 
      Le distributeur affiche un message "demandant le code de la carte"
      Le client tape son code 
