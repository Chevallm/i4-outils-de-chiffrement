# Memento OpenSSL
- auteur: Maxime Chevallier-Pichon
- date: 03.10.2017
- intervenant: Anthony Masset

# Usage

Pour chiffrer

```$ openssl enc -aes-256-cbc -in {nomDuFichierDEntree} -out {nomDuFichierDeSortie}```


Pour dechiffrer

```$ openssl enc -d -aes-256-cbc -in {nomDuFichierDEntree} -out {nomDuFichierDeSortie}```
