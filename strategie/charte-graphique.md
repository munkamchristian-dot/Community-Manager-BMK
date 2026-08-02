# Charte graphique — BMK Architects

> Fichier canonique de la charte visuelle. Tout agent produisant un brief visuel, un prompt de génération d'image ou une spécification de mise en page doit lire ce fichier en premier et s'y conformer. Remplace et corrige la charte initiale (qui utilisait un accent terracotta) — mise à jour le 2 août 2026 à la demande de la direction, pour aligner l'accent de marque sur la vraie couleur du logo BMK.

## Couleurs

| Rôle | Valeur | Statut |
|---|---|---|
| Fond | Blanc cassé `#F5F4F1` | Inchangé |
| Texte principal / structure | Anthracite `#1E1E1C` | Inchangé |
| Neutre secondaire (légendes, numérotation) | `#B8B5AE` | Inchangé |
| **Accent de marque** | **Vert `#73c34a`** | **Changé — remplace l'ancien terracotta `#B5651D` partout, y compris l'alternative bleu nuit institutionnelle qui est abandonnée** |

**Règle stricte :** partout où une spécification antérieure (brief visuel d'août, prompts IA) mentionne du terracotta `#B5651D` ou du bleu nuit `#1F3A5F`, remplacer par le vert `#73c34a`. Le fond, le texte anthracite et tout le reste de la mise en page ne changent pas.

## Logo

Le logo réel de BMK Architects a été fourni par la direction (fichier image) : un monogramme « B▲▲K » où le B et le K sont en noir plein, et les deux sommets centraux forment deux triangles superposés façon pics de montagne — le triangle de gauche en anthracite/gris foncé, le triangle de droite en vert `#73c34a`, avec une zone de recouvrement plus sombre au centre. En dessous, le mot « Architects » en noir, dans une police fine.

**Statut du fichier logo :** récupéré et versé dans le dépôt sous `assets/logo/bmk-logo.png` (2000×889 px, fond transparent, vert vérifié conforme à `#73c34a`). C'est ce fichier qui doit être utilisé pour toute incrustation en post-production.

**Pour les prompts de génération IA :** les générateurs d'image ne reproduisent pas fidèlement un logo existant à partir d'une simple description texte. Sauf si l'outil utilisé accepte une image de référence en entrée (upload direct du fichier `assets/logo/bmk-logo.png` en complément du prompt texte, ce que permettent ChatGPT et Nano Banana/Gemini via leurs fonctions d'édition/composition à partir d'image), chaque prompt continue à réserver un espace vide en bas à droite (repère générique triangle/pic de montagne minimaliste dans les couleurs de la charte) — le vrai logo est alors incrusté en post-production à partir du fichier du dépôt, jamais généré par l'IA à partir de zéro.

## Coordonnées de marque à afficher

Deux éléments doivent apparaître de façon cohérente sur les visuels, en plus du logo :

- **Site web :** www.bmkarchitects.com
- **Compte Instagram :** @bmkarchitects

**Règle de placement :** sur la slide de couverture ou de clôture de chaque publication (carrousel) — ou en bas du visuel pour un post simple — afficher une petite ligne de coordonnées regroupant le site et le compte Instagram, en texte discret (taille inférieure au corps de texte principal), dans la couleur neutre secondaire `#B8B5AE` ou l'anthracite `#1E1E1C`. Ne pas les répéter sur les slides intermédiaires d'un carrousel (titre/contenu) pour ne pas surcharger — uniquement cover et/ou clôture.

## Exigences de production des visuels générés par IA

- **Chaque slide doit être produite comme un fichier image distinct**, jamais un montage combiné de plusieurs slides dans une seule image.
- **Qualité maximale disponible, visée « 4K »** : demander explicitement au générateur la plus haute résolution/qualité possible, netteté maximale, rendu qualité impression. À noter pour la direction : la plupart des générateurs grand public (ChatGPT/GPT-image, Nano Banana/Gemini) plafonnent leur résolution native en dessous d'un vrai 4K pixel pour un format portrait 4:5 — si le rendu obtenu est plus petit que souhaité, passer l'image dans un outil d'upscaling (ex. fonctionnalité d'agrandissement de Canva, ou un outil dédié) avant usage final.

## Format et typographie (inchangés)

- Format : 1080×1350 px minimum (ratio 4:5 portrait), à générer en plus haute résolution possible dans ce même ratio.
- Typographie : sans-serif géométrique — Bold (titres), Semibold (sous-titres), Regular (texte courant).

---

*Ce fichier fait foi pour toute production visuelle future. Toute nouvelle charte ou évolution doit être versée ici par le `directeur-marketing`, pas seulement transmise oralement dans une conversation.*
