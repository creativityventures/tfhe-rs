# 01 — Types de ciphertexts TFHE

TFHE-rs propose plusieurs niveaux d API, des primitives courtes aux entiers chiffres de haut niveau.
Un ciphertext ne porte pas seulement une valeur cachee : ses parametres, son bruit et son type conditionnent les operations valides.
Les clefs client chiffrent et dechiffrent ; les clefs serveur permettent le calcul sans donner acces au clair.
Partager une clef serveur elargit la capacite de calcul, pas la capacite de dechiffrement.
La revue doit suivre type, parametres et domaine de chaque valeur a travers les conversions.
Une conversion implicite ou un mauvais jeu de parametres peut casser correction ou securite.
Source : [`tfhe/src`](https://github.com/zama-ai/tfhe-rs/tree/main/tfhe/src).

[Suite : bootstrap](02-bootstrap-programmable.md)
