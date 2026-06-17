# Magic Chrono - Brain Storm V15 Proxy Hybrid

Basé sur le code fourni par l'autre IA, avec AllOrigins comme proxy de secours.

## Changements

- Essaie d'abord l'API directement.
- Si la lecture directe échoue, utilise `https://api.allorigins.win/get?url=...`.
- Si l'API est vide ou en erreur, passe en secours manuel :
  - `PPxx`, exemple `3900` = Stop 39.
  - Appel d'urgence = mode `PPJJMM`, exemple `392906` = Tour 29, Tour 06, Stop 39.
- Si API OK, le PIN reste camouflage 4 chiffres.
- Anniversaire accepté : `(29/06)` ou `29/06`.
- Désactive les anciens service workers/caches.
