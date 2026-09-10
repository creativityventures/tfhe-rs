# 03 — Entiers chiffres et propagation

Les entiers sont decomposes en blocs chiffres avec message et retenue.
Additionner ou multiplier peut accumuler des retenues qui doivent etre propagees avant certaines operations suivantes.
Les API de haut niveau masquent une partie de cette mecanique, mais les couts et bornes restent reels.
Les versions signees et non signees different pour comparaisons, debordements et interpretation du bit de signe.
Une application doit fixer largeur, comportement de debordement et resultat attendu pour les valeurs limites.
Les tests metier futurs doivent couvrir zero, maximum, changements de signe et retenues saturees.
Source : [`tfhe/src/integer`](https://github.com/zama-ai/tfhe-rs/tree/main/tfhe/src/integer).

[Suite : parametres](04-parametres-et-securite.md)
