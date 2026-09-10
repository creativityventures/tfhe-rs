# 02 — Bootstrap programmable

Le bootstrap programmable reduit le bruit tout en evaluant une fonction sur le message chiffre.
Cette operation rend possibles des chaines de calcul longues, au prix d un cout nettement superieur aux operations lineaires.
Le codage du message, le polynome test et la decomposition doivent etre compatibles avec les parametres cryptographiques.
Une erreur de plage peut produire un resultat mathematiquement valide mais semantiquement faux pour l application.
Les comparaisons et selections chiffrees reposent souvent sur cette capacite et doivent etre budgetees explicitement.
Optimiser le nombre de bootstraps ne doit pas modifier la fonction calculee.
Sources : [`tfhe/src/core_crypto`](https://github.com/zama-ai/tfhe-rs/tree/main/tfhe/src/core_crypto) et [`tfhe-fft`](https://github.com/zama-ai/tfhe-rs/tree/main/tfhe-fft).

[Suite : entiers](03-entiers-et-propagation.md)
