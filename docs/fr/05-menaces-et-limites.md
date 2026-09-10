# 05 — Menaces, licences et limites

Le chiffrement homomorphe protege les donnees pendant le calcul, pas automatiquement les metadonnees, la disponibilite ou les clefs aux extremites.
Le README indique que les mitigations contre les canaux auxiliaires ne sont pas encore implementees.
Les applications sensibles doivent donc isoler la generation de clefs et le dechiffrement, et evaluer leur propre exposition temporelle ou materielle.
La licence BSD-3-Clause-Clear et les conditions de brevet demandent une verification specifique avant usage commercial.
Les changements de parametres exigent une strategie explicite de compatibilite ou de rechiffrement.
Ce parcours est documentaire, pas un audit. Aucune installation, compilation ou execution de tests n a ete effectuee.
Sources : [`SECURITY.md`](https://github.com/zama-ai/tfhe-rs/blob/main/SECURITY.md) et [`README.md`](https://github.com/zama-ai/tfhe-rs/blob/main/README.md).

[Retour au sommaire](README.md)
