# MagiChrono - Brain Storm V5.18

Correctif comportement du bouton Appel d'urgence.

## Changement principal

Quand l'app est en secours manuel parce que l'API était vide ou inaccessible, le bouton **Appel d'urgence** fait maintenant :

1. relire l'API ;
2. si l'API a reçu une position, revenir en mode API sans switch manuel ;
3. seulement si l'API est encore vide / erreur, switcher entre secours position `PPxx` et secours annif `PPJJMM`.

Le branding, le footer, l'encodage, le proxy AllOrigins, le texte discret et la sécurité START - STOP - RESET sont conservés.
