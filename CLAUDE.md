# Wireframe Moss — Contexte Projet

## Infos générales
- **Dossier** : `~/cloud1/deployed-apps/wireframe-moss/`
- **URL publique** : `https://nexuserv.duckdns.org/apps/wireframe-moss/`
- **Projet lié** : `projet-moss` (Symfony, `nexuserv:8082`)
- **Dernière mise à jour** : 2026-04-01

## Structure des fichiers
- `index.html` — **Hub principal** (accueil avec cartes vers tous les documents)
- `index2.html` — **Wireframes des pages** (maquettes style Figma, refaits le 01/04)
- `index2_backup.html` — Backup des anciens wireframes avant refonte
- `index3.html` — **Architecture** technique
- `index4.html` — **Guide des animations** (peu pertinent, juste transitions CSS)
- `index5.html` — **Planning** (inventé, pas réaliste — Arnaud n'a suivi aucun planning)
- `presentation.html` — **Diaporama** examen (PowerPoint converti en HTML)
- `dossier-professionnel/index.html` — **Dossier professionnel** d'Arnaud (199 Ko)
- `cahier-des-charges-fusionne/index.html` — **Cahier des charges fusionné** (43 pages, 136 Ko+)

## PDFs sources
- `cahier-des-charges-final.pdf` (4 Mo) — PDF original cahier des charges
- `CAHIER_DES_CHARGES_PAGES_9-39.pdf` (425 Ko) — Extrait pages 9-39
- `MossAir_Presentation.pptx` / `.pdf` — PowerPoint de présentation

## Cahier des charges fusionné — État actuel (43 pages)
- **Pages 1-30** : Contenu initial (couverture, intro, technique, MCD, controllers, templates, etc.)
- **Pages 31-40** : Gamme produits, parcours perso, personas, histoire/à propos, footer, commandes, admin, stock, wireframes, newsletter, perspectives
- **Pages 40-43** : Wireframes desktop/mobile/tablette + architecture + table des matières

### TODO (à faire) :
1. **Déplacer la table des matières** — actuellement page 5, doit être page 2 (juste après couverture, avant l'intro)
2. **MCD interactif** — dessiner les relations entre tables (lignes + cardinalités). Nécessite Arnaud devant l'écran
3. **Intégrer vrais screenshots** — 6 placeholders gris à remplacer quand Arnaud envoie les images
4. **Planning et animations** — à ignorer/supprimer (planning inventé, animations = juste hover CSS)

### Ce qui a été fait (session 01/04) :
- Fusion des 2 PDFs + PowerPoint en un seul document HTML navigable (43 pages)
- Carte ajoutée dans le hub principal (orange/doré)
- Wireframes refaits (index2.html) : 12 desktop, 7 mobile, 2 tablette
- Backup des anciens wireframes (index2_backup.html)
- Ajout gamme produits, parcours, personas, bilan & perspectives
- Dossier pro d'Arnaud remplace celui de Najiba

## Notes importantes
- **NE PAS toucher** aux PDFs sources
- **index4.html (animations)** et **index5.html (planning)** = peu fiables, pas à intégrer dans le cahier
- Les wireframes (index2.html) ont été refaits pour correspondre au vrai site Symfony final
- Le MCD n'a pas encore les lignes de relations entre tables
