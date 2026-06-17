# MagiChrono V5.27

V5.27 = base stable V5.25 + Forcing Laps repris prudemment du fichier fourni.

Forcing Laps :
- Code de base `LLSS`.
- Appui court Appel d'urgence : ajoute 2 chiffres.
- Appui long Appel d'urgence : retour à 4 chiffres.
- Dernière paire `SS` = somme forcée au Stop.
- `SS=00` = vrai Stop chrono.
- `0000` = suite prédéfinie dans les paramètres.

Sécurité :
- Pavé numérique vérifié.
- Script fallback clavier ajouté pour éviter l'écran sans clavier.
- JavaScript vérifié avec node --check.
- Multi-cartes Position Time, Cut Deck, Brain Storm, Mnemonica et encodage conservés.
