# MagiChrono V5.23

Correctif urgent : le pavé numérique disparaissait dans V5.22 à cause d'un script trop fragile.

Changements conservés :
- Forcing Laps avec format `LLSS`, `L1L2SS`, `L1L2L3SS`.
- `SS=00` = vrai Stop chrono.
- Appel d'urgence court = ajoute 2 chiffres.
- Appel d'urgence maintenu = retour à 4 chiffres.
- Mnemonica corrigé.
- Brain Storm API, annif, proxy, encodage, anti-double tap, START-STOP-RESET.

Contrôle technique : JavaScript validé avec `node --check`.
