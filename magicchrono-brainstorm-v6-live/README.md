# Magic Chrono - Brain Storm V6 Live

Correctifs :

- Relit l'API toutes les 1,5 secondes pendant l'écran PIN Brain Storm.
- Relit encore l'API au moment où le PIN est validé.
- Ajoute `_t` et `r` dans l'URL pour éviter le cache.
- Lit `birthday` et aussi Message/full_peek pour le mode anniversaire.
- Affiche `TP=...` et `timeUpdated` sur l'écran PIN pour vérifier que la valeur change.

Si TP ne change pas alors que l'API change dans le navigateur, il faudra vérifier le cache du téléphone/PWA.
