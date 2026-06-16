# Magic Chrono - Brain Storm V7 Stable

Correctifs par rapport à V6 :

- Suppression du polling toutes les 1,5 secondes, car cela pouvait provoquer une erreur API après un premier succès.
- Suppression des headers `Cache-Control` et `Pragma`, qui peuvent déclencher un preflight CORS.
- L'API est lue à l'ouverture du PIN et relue une fois à la validation du PIN.
- Si l'API échoue après un premier succès, l'app conserve la dernière bonne valeur en secours.
- Le mode anniversaire lit `birthday`, `Message1`, `Message2`, `full_peek`, `text`.
