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

## Style illustré BD de référence — validé par la direction le 3 août 2026

Historique bref : une première piste « planche BD encrée, hachures croisées, visages expressifs » avait été testée sur le sketch 3 (v9) puis abandonnée au profit d'un retour au line-art épuré « spot » sans visage (v10). La direction a ensuite généré elle-même un visuel à partir du prompt v10 du slide 7/8, et le résultat obtenu — plus riche que ce qui était demandé — est celui qu'elle valide et adore. **Ce visuel devient la référence de style officielle pour toute production de type bande dessinée/carrousel comique (pilier conseil, Publication 5 et toute production BD future).** Il ne s'applique pas aux carrousels pédagogiques/pictogrammes purs (Publications 1 à 4, pilier pédagogique), qui restent en line-art minimal sans personnage détaillé selon le reste de cette charte.

**Caractéristiques précises à reproduire et à affiner pour plus de qualité encore :**

- **Avatars circulaires à visage détaillé et expressif**, en line-art fin et propre (traits nets, pas de hachures denses, pas de style franco-belge caricatural épais) : contrairement à la convention « avatar sans trait de visage » utilisée jusqu'ici, le personnage a un visage dessiné avec de vraies expressions (sourire chaleureux et yeux plissés pour la satisfaction/l'enthousiasme, sourcils froncés + bouche entrouverte + main sur la tête pour la surprise/l'inquiétude) — expression toujours lisible immédiatement, jamais outrancière.
- **Petites lignes de mouvement/éclat fines autour du cercle de l'avatar** (traits courts rayonnants) pour dynamiser la pose, en anthracite fin.
- **Pictogramme de rôle accolé au cercle** (casque de chantier pour l'entrepreneur, crayon + équerre pour l'architecte) et **étiquette de rôle en capitales grasses** sous l'avatar.
- **Bulle de dialogue à coins arrondis**, contour fin anthracite, fond blanc cassé, texte sans-serif clair — seuls les guillemets et le point d'exclamation/la ponctuation forte sont accentués en vert `#73c34a`.
- **Arrière-plan scénique détaillé en line-art**, pas un simple pictogramme minimal : une véritable illustration de scène (ex. chantier avec grue, base-vie, matériaux, structure en construction, gravats pour une scène de désordre) qui pose le décor narratif tout en restant en trait fin anthracite sur fond `#F5F4F1`, sans couleur autre que les touches vertes ponctuelles.
- **Listes de constats en ligne** : chaque élément précédé d'une petite icône combinée (regard écarquillé + pictogramme illustrant l'élément cité), alignée avec un texte court — une ou deux touches vertes ponctuelles seulement (petit trait, tiret), jamais un aplat.
- **Typographie** : labels en gras condensé capitales, texte de bulle/liste en regular/semibold — cohérent avec le reste de la charte.
- **Règle du vert inchangée** : `#73c34a` uniquement en touches ponctuelles (guillemets, exclamation, petits traits/tirets d'accent) — jamais un aplat de fond, une case colorée ou une grande zone de couleur.

**Consigne pour les prompts futurs :** reprendre fidèlement cette structure visuelle en l'améliorant pour plus de qualité et de fiabilité de génération (proportions cohérentes d'un slide à l'autre, netteté, richesse du décor sans surcharge, expressions toujours lisibles) — c'est désormais la base par défaut pour toute la Publication 5, à appliquer de façon cohérente sur les 8 slides (sketchs 1, 2 et 3), pas seulement sur le sketch 3.

## Format et typographie (inchangés)

- Format : 1080×1350 px minimum (ratio 4:5 portrait), à générer en plus haute résolution possible dans ce même ratio.
- Typographie : sans-serif géométrique — Bold (titres), Semibold (sous-titres), Regular (texte courant).

---

*Ce fichier fait foi pour toute production visuelle future. Toute nouvelle charte ou évolution doit être versée ici par le `directeur-marketing`, pas seulement transmise oralement dans une conversation.*
