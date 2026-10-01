# Hachette Collections Studio — démo structurelle

Cette démo Hachette Collections est un outil indépendant. Son interface d’atelier reprend les principes ergonomiques éprouvés dans F2K, sans relier les deux produits.

## Déjà en place

- navigation Accueil / Collections / Ateliers ;
- deux collections initiales ;
- banque d’assets locale par collection ;
- import d’images avec choix original ou demande de détourage ;
- six ateliers correspondant au brief ;
- éditeur intégré noir et gris, affiché dans la même page que le choix des ateliers ;
- compositions initiales pour les six ateliers du brief ;
- déplacement, édition et gestion élémentaire des calques ;
- sauvegarde locale des projets par atelier ;
- cinq fonds officiels fournis pour « Disney — Romans Inoubliables » ;
- copyright automatique « © 2025 Disney » pour cette collection ;
- identité globale Hachette Collections.

## Prochaine étape

Intégrer les assets officiels des deux collections, puis connecter chaque atelier à ses layouts, formats et comportements automatiques dédiés.

## Aperçu local

Depuis ce dossier :

```bash
python3 -m http.server 8765 --bind 127.0.0.1
```

Puis ouvrir `http://127.0.0.1:8765/`.
