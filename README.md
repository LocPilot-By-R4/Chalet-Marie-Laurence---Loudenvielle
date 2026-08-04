# Chalet de Louron — v20 informations corrigées

Version issue de la v19, avec les informations capacité / parking / sanitaires corrigées sur les trois langues.

Corrections v20 :
- capacité affichée : 9 à 10 personnes ;
- données structurées mises à jour avec `maximumAttendeeCapacity: 10` ;
- parking corrigé : 4 places de parking ;
- sanitaires corrigés : 2 salles d’eau + 2 WC séparés ;
- traductions FR / EN / ES mises à jour ;
- métadonnées SEO / Open Graph / llms.txt mises à jour ;
- visite virtuelle 360 plein écran conservée ;
- arborescence LocPilot / Alice conservée.

## v21 — Miniatures visite virtuelle 360°

Les miniatures de la galerie 360° ont été régénérées depuis les panoramas équirectangulaires sous forme de vues rectilinéaires 16:9. Elles ne sont plus de simples panoramas écrasés dans une vignette.

Principe retenu : ne pas initialiser un viewer Photo Sphere Viewer/WebGL dans chaque miniature afin de préserver les Core Web Vitals. Les vignettes servent d’aperçu léger ; au clic, la scène complète s’ouvre dans le viewer 360°.


## V25 - Correction cache miniatures

Les miniatures des sections activités et visite 360 ont été renommées avec le suffixe `-v25.webp` afin de forcer le navigateur à charger les nouvelles images et éviter l’affichage d’anciennes vignettes mises en cache.
