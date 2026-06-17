# MagiChrono - Brain Storm V5.22

Modification Forcing Laps.

## Nouveau format PIN Forcing Laps

- Code de base 4 chiffres : `LLSS`.
  - `LL` = centièmes du premier tour.
  - `SS` = somme finale forcée au Stop.
- Appel d'urgence court : ajoute 2 chiffres, donc un lap de plus.
  - 6 chiffres : `L1L2SS`.
  - 8 chiffres : `L1L2L3SS`.
- Appel d'urgence maintenu : retour à 4 chiffres.
- Si `SS = 00`, pas de forçage au Stop : vrai stop chrono.
- `0000` utilise les paramètres prédéfinis.

Les corrections précédentes sont conservées : Mnemonica, Brain Storm API, proxy, annif, anti-double tap, encodage, START-STOP-RESET.
