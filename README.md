# Magic Chrono - Brain Storm V8 Clean

Cette version évite les comportements instables :

- lit l'API à l'ouverture du PIN uniquement ;
- bouton Appel d’urgence = relire l'API manuellement ;
- ne lance pas le chrono si `TargetPosition` vaut `0` ;
- ne relit pas automatiquement au moment du PIN, pour éviter de remplacer une bonne valeur par une erreur ;
- lit l'anniversaire depuis `birthday`, `Message1`, `Message2`, `full_peek`, `text`.
