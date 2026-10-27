# Résidence Henri Clérisse – maquette 3D interactive

Maquette 3D légère (≈ 0,5 Mo de géométrie) de la résidence, générée depuis l'IFC Revit du projet.
Fonctionne dans un navigateur (ordinateur, tablette, smartphone), sans installation.

- Vues : Complet, ou coupes R+3 / R+2 / R+1 / RDC (sections de murs en noir plein).
- 30 logements cliquables : surfaces, pièces, plan de vente consultable en fenêtre.
- Soleil réglable (date + heure, du lever au coucher) avec ombres portées.
- Abords : bâtiments, rues, trottoirs, marquages et arbres (OpenStreetMap, recalés sur le plan masse du PC).

Ouvrir `index.html` via un serveur statique (les modules JavaScript ne se chargent pas en `file://`) :

```bash
python -m http.server 8000
```

## Crédits et licences

- Fond de carte : © contributeurs OpenStreetMap, licence ODbL – https://www.openstreetmap.org/copyright
- Rendu 3D : three.js (MIT). Compression : meshopt.
- Plans de vente et plans du permis : SAJAC Immobilier / DND Architectes – documents de communication du projet.
