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

**Pour les prompts de génération IA :** les générateurs d'image ne reproduisent pas fidèlement un logo existant à partir d'une simple description texte, et rendent le texte en général de façon peu fiable (accents français en particulier). **Décision de la direction (2 août 2026) : le logo n'est plus mentionné du tout dans les prompts de génération.** Les prompts ne demandent que le contenu principal (titre, sous-titre, illustration) ; le logo est ajouté entièrement en post-production sous Photoshop à partir de `assets/logo/bmk-logo.png`, sur chaque slide, par la direction.

## Coordonnées de marque à afficher

Deux éléments doivent apparaître de façon cohérente sur les visuels publiés, en plus du logo :

- **Site web :** www.bmkarchitects.com
- **Compte Instagram :** @bmkarchitects

**Règle de placement (mise à jour du 2 août 2026) :** ces coordonnées, ainsi que le hashtag `#BmkArchitects`, **ne sont plus demandées dans les prompts de génération d'image** — la direction a jugé plus fiable de les ajouter elle-même sous Photoshop en post-production sur chaque slide, plutôt que de laisser l'IA tenter de les écrire (risque de texte déformé ou de mentions non désirées). Emplacement recommandé pour l'ajout manuel : en bas du visuel, sur la slide de couverture et/ou de clôture pour un carrousel, en bas du visuel pour un post simple ; texte discret, couleur `#B8B5AE` ou `#1E1E1C`. Ne pas les répéter sur les slides intermédiaires d'un carrousel.

## Exigences de production des visuels générés par IA

- **Chaque slide doit être produite comme un fichier image distinct**, jamais un montage combiné de plusieurs slides dans une seule image.
- **Qualité maximale disponible, visée « 4K »** : demander explicitement au générateur la plus haute résolution/qualité possible, netteté maximale, rendu qualité impression. À noter pour la direction : la plupart des générateurs grand public (ChatGPT/GPT-image, Nano Banana/Gemini) plafonnent leur résolution native en dessous d'un vrai 4K pixel pour un format portrait 4:5 — si le rendu obtenu est plus petit que souhaité, passer l'image dans un outil d'upscaling (ex. fonctionnalité d'agrandissement de Canva, ou un outil dédié) avant usage final.

## Style BD de référence — Sketch 3 (Publication 5, pilier conseil)

Référence visuelle fournie par la direction le 2 août 2026 (planche BD classique franco-belge en noir et blanc) pour calibrer le rendu du sketch 3 (« Le chantier », slides 7/8 et 8/8). Caractéristiques à reproduire impérativement dans les prompts de ce sketch :

- **Dessin entièrement encré à la plume, noir et blanc** — aucun aplat de couleur lisse, aucun dégradé numérique. Tous les volumes et les ombres sont construits par **hachures croisées denses** (cross-hatching manuel), avec des réseaux de traits fins qui se superposent pour créer les zones sombres.
- **Trait de contour irrégulier, à épaisseur variable**, visiblement tracé à la main (jamais une ligne vectorielle parfaitement lisse ou uniforme) — petites imperfections, légers tremblés, contours qui s'épaississent dans les zones d'ombre.
- **Personnages caricaturaux mais attachants**, dans la tradition de la BD humoristique franco-belge classique : visages expressifs très marqués, nez et traits accentués pour l'effet comique, postures et gestuelles exagérées au service du gag, sans jamais tomber dans la moquerie agressive.
- **Ombres portées profondes** obtenues uniquement par la densité des hachures (jamais par un aplat noir plat ni un dégradé), créant un fort contraste noir/blanc.
- **Cases aux bords fins et nets**, bulles de dialogue dessinées à la main avec un lettrage BD classique (majuscules, légèrement irrégulières).
- **Le vert `#73c34a` reste réservé à de très petites touches fines uniquement** (guillemets, point d'exclamation, un ou deux petits traits d'accent) — il ne doit jamais devenir un aplat de fond, une case colorée ou une zone de couleur, y compris dans ce style BD plus dense. Le reste du dessin reste en noir/blanc/hachures.

Cette rupture de style (dessin dense à la plume, hachuré) est assumée et limitée au sketch 3 de la Publication 5 — elle ne s'applique pas aux autres slides des piliers conseil et pédagogique, qui restent en line-art fine épurée sur fond `#F5F4F1` selon le reste de cette charte.

## Format et typographie (inchangés)

- Format : 1080×1350 px minimum (ratio 4:5 portrait), à générer en plus haute résolution possible dans ce même ratio.
- Typographie : sans-serif géométrique — Bold (titres), Semibold (sous-titres), Regular (texte courant).

---

*Ce fichier fait foi pour toute production visuelle future. Toute nouvelle charte ou évolution doit être versée ici par le `directeur-marketing`, pas seulement transmise oralement dans une conversation.*
