# Projet CV public — Instructions Claude Code

## Contexte
CV public de Paul Fretté, publié par GitHub Pages (`paulfrettepro-collab.github.io/cv`, dépôt PUBLIC) et lié depuis
son profil GitHub. Version neutre, commune à toutes les pistes : les CV ciblés vivent dans
`~/Github_pro_folder/candidatures/dossiers/<piste>/output/` (dépôt privé).

## Règles (Paul, 28/10/2026)
- Branding neutre : gabarit une colonne du skill `cv-candidature-pro`, un seul accent (#1f3a5f). Jamais la charte
  d'un employeur.
- Anglais, une page A4. `index.html` sert à la fois l'écran (feuille centrée, téléphone) et le PDF.
- Faits seulement : `candidatures/input/01_faits_carriere_verifies/`. Rien d'inventé pour combler un trou.
- Dépôt public : pas de téléphone, pas de roadmap d'un tiers, pas de client public nommé sans accord de Paul.
- PDF : `"/Applications/Google Chrome.app/Contents/MacOS/Google Chrome" --headless=new --disable-gpu
  --no-pdf-header-footer --print-to-pdf=Paul_Frette_CV.pdf file://$PWD/index.html`, puis `pdfinfo` (1 page) et
  `pdffonts` (CID TrueType).
- Publier (push) seulement sur GO de Paul : le push met la page en ligne.

## Stack
- HTML/CSS pur, police système Helvetica Neue, sans dépendance

## Historique du projet

**OBLIGATOIRE** : A chaque session de travail sur ce projet :

1. **En debut de session** : lire `HISTORIQUE.md` a la racine pour reprendre le contexte
2. **En fin de session** (ou apres chaque action significative) : ajouter une entree datee dans `HISTORIQUE.md` avec :
   - Date et titre de l'action
   - Ce qui a ete fait (actions, analyses, productions)
   - Decisions prises
   - Livrables crees ou modifies
   - Prochaines etapes identifiees
3. **Mettre a jour la section "En attente"** en bas du fichier (cocher ce qui est fait, ajouter les nouveaux points)
