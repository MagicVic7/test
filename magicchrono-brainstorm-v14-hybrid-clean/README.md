# Magic Chrono - Brain Storm Hybrid V14 Clean

Approche propre et isolée : uniquement le tour Brain Storm.

- API d’abord : lit `TargetPosition`, `birthday`, `full_peek`, `text`, `timeUpdated`.
- Si API OK : PIN camouflage 4 chiffres.
- Si API vide ou erreur : secours manuel `PPxx`.
- Appel d’urgence en secours : `PPJJMM`.
- Pas de service worker actif pour éviter le cache.
