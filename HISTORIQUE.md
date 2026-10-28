# Historique — CV public

> Ce fichier est mis à jour automatiquement par Claude Code à chaque session de travail.
> Ne pas supprimer les entrées existantes.

---

## 2026-10-28 — Refonte neutre du CV public

- **Demande de Paul** : CV public neutre, actualisé avec ses dernières candidatures, branding neutre (plus la charte Data Inceptio).
- **Fait** : `index.html` refait sur le gabarit une colonne du skill `cv-candidature-pro`, en anglais, une page A4, lisible sur téléphone ; `Paul_Frette_CV.pdf` généré depuis la même page (lien « Download PDF »).
- **Contenu** : repris du CV Salesforce du 23/10 et des CV Alan / Mistral du 17/10 ; ajout des directeurs de la Région formés en octobre 2026 et des lignes 2024 validées par Paul le 17/10 (bootcamp, rénovation).
- **Retiré de la version publique** : téléphone, section « Engagement filière musicale », nom de la Région, item de roadmap du vendeur de la plateforme, charte Data Inceptio.
- **Contre-expertise** : `claude_ask.py --tier decision` (Fable 5.1). Retenu : trou 2024 comblé, résumé réécrit (valeur actuelle d'abord), moins de noms de produits, roadmap tierce retirée, Région anonymisée, « Signify (formerly Philips Lighting) ». Non retenu : arrondir les chiffres vérifiés, changer les intitulés sans comparer à LinkedIn, ajouter « open to Paris / remote » (non validé par Paul).
- **Piège** : le PDF du 23/10 tenait sur une page parce que la ligne de contact (avec le téléphone) dépassait et faisait réduire la page par Chrome (~0,96). Sans le téléphone, l'échelle est posée en `zoom: 0.96` dans `@media print`.

---

## 2026-04-27 — Ajout section "Engagement filière musicale"

- **Action** : Ajout d'une nouvelle section dans `index.html` valorisant le profil d'acteur de la filière musicale française de Paul (production Maschine 3 / Ableton Live, DJ associatif, collectif organisateur, réseau mobilisable).
- **Contexte** : Préparation de la candidature Data Inceptio à l'AO CNM 2026-06 (étude impact IAG sur filière musicale, dépôt 5 mai 2026). Le CV enrichi sera annexé au CRT pour démontrer la double casquette data engineer + acteur filière, différenciant majeur sur le sous-critère 1.1 "moyens humains et techniques" (30% pondération).
- **Design** : section dédiée respectant la charte refondue (variables CSS Data Inceptio, police Sora, sans emojis dans les titres). Bloc `experience-item` standard avec `exp-tech` (Maschine 3, Ableton Live 11 & 12, Suno, Udio, Sound design, DJing) et `key-figures` pour les liens publics (Instagram @paulft_music, SoundCloud plaizan1994).
- **Décisions** : section autonome (vs intégration dans Expériences Pro) pour mettre en valeur l'angle unique. Insérée entre "Expériences Professionnelles" et "Projets" dans le flux du CV.
- **Livrables modifiés** : `index.html`

---

## 2026-03-24 — Refonte complète du CV

- **Action** : Réécriture intégrale de `index.html` pour un CV honnête et représentatif
- **Design** :
  - Migration vers la charte Data Inceptio (couleurs #34184F/#431F66/#512DA8, champagne, lavande)
  - Police Sora (Google Fonts) remplaçant Segoe UI
  - Suppression de tous les emojis, design professionnel épuré
- **Contenu — Suppressions (compétences surestimées)** :
  - LangChain, LlamaIndex, Kubernetes, Snowflake, Looker, Azure, MongoDB
  - Profil "10+ années d'expérience" en data (remplacé par "7 ans business + reconversion")
  - "Fine-tuning de modèles", "migration cloud", "pipelines ETL scalables (Azure, AWS, GCP)"
- **Contenu — Ajouts (travail réel)** :
  - Projet GREENOV RO2B2 (consortium EU, architecture data, DINOv2+SVM)
  - 14 agents IA Swiftask (REST + GraphQL, RAG, orchestration multi-agents)
  - Intégrations M365 Bridge (MSAL/OAuth), Odoo ERP (XML-RPC), Notion API
  - Formation IA Entreprise (Copilot, 4 niveaux pédagogiques)
  - Section "Projets" avec liens GitHub et démo Streamlit live
  - Lien GitHub dans le header et le footer
  - Catégorie compétences "APIs & Intégrations" (REST, GraphQL, XML-RPC, MSAL, Microsoft Graph, Selenium)
- **Livrables** : `index.html` (refonte complète)

---

## 2026-03-04 — Initialisation de l'historique

- **Action** : Création du système de suivi CLAUDE.md + HISTORIQUE.md
- **Livrables** : `CLAUDE.md`, `HISTORIQUE.md`

---

## En attente

- [ ] Ajouter les notes d'évaluation des formations IA clients (scores à fournir par Paul)
- [x] Ajouter URL LinkedIn dans le header (fait 2026-10-28)
- [x] Ajouter section "Engagement filière musicale" pour annexion CRT CNM (fait 2026-04-27)
- [ ] Trou juin–novembre 2025 : à couvrir si Paul a un fait à mettre (rien dans les faits vérifiés)
- [ ] Intitulés à comparer avec LinkedIn (« Data Architect », « CRM Data Analyst »)
