# 04 — Parametres, probabilite d echec et securite

Les jeux de parametres arbitrent securite, precision, probabilite d echec et performance.
La securite estimee depend d un modele d attaque et d une version de l estimateur de reseaux.
La probabilite de panne cryptographique n est pas une exception logicielle ordinaire : elle doit etre compatible avec le volume total d operations.
Le depot annonce pour l API haut niveau des ensembles visant une probabilite au plus egale a 2^-128 dans son modele par defaut.
Cette valeur ne couvre ni erreurs d integration, ni fuite de cle, ni canal auxiliaire.
Les parametres doivent etre pris dans les presets documentes et versionnes avec les donnees chiffrees.
Sources : [`tfhe/src/shortint/parameters`](https://github.com/zama-ai/tfhe-rs/tree/main/tfhe/src/shortint/parameters) et [`README.md`](https://github.com/zama-ai/tfhe-rs/blob/main/README.md).

[Suite : limites](05-menaces-et-limites.md)
