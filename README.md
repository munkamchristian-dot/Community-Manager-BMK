# Community-Manager-BMK

Système d'agents Claude Code pour la stratégie marketing et la présence Instagram de **BMK Architects** (cabinet d'architecture, Yaoundé, Cameroun).

## Structure

```
strategie/
  BRIEF-BMK.md              # Base de connaissances condensée (à lire par tous les agents)
  calendrier-editorial.md   # Calendrier de publication Instagram, tenu à jour par directeur-marketing
  documents/                # Les 4 documents marketing complets (.docx)
    01_Contexte_Entreprise_BMK.docx
    02_Communication_SWOT_BMK.docx
    03_Offres_Services_BMK.docx
    04_Analyse_Concurrentielle_BMK.docx

.claude/agents/
  directeur-marketing.md    # Agent principal — orchestrateur, ne rédige presque jamais lui-même
  redacteur-contenu.md      # Sous-agent — légendes et textes
  directeur-artistique.md   # Sous-agent — briefs visuels
  community-engagement.md   # Sous-agent — brouillons de réponses, veille communauté
  analyste-performance.md   # Sous-agent — lecture des indicateurs, recommandations
```

## Comment ça marche

Invoque l'agent `directeur-marketing` pour toute demande stratégique ("planifie le contenu Instagram du mois", "quelle stratégie pour mettre en avant nos projets institutionnels", "revois ce brouillon avant publication"...). Il consulte `strategie/BRIEF-BMK.md`, pose des questions si besoin pour clarifier les objectifs, puis délègue la production concrète aux sous-agents appropriés et fait le contrôle qualité final. Il ne publie jamais directement sur Instagram — la publication reste une action humaine.

Les sous-agents sont des exécutants spécialisés : ils reçoivent un brief autonome (ils n'ont pas accès à la conversation en cours) et rendent un livrable, sans décider de la stratégie.

## Mettre à jour la base de connaissances

Si de nouvelles informations sur BMK Architects sont fournies (captures d'écran, données Instagram, nouveaux projets...), mettre à jour `strategie/BRIEF-BMK.md` en conséquence pour que tous les agents en héritent dans les sessions futures.
