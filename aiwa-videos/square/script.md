# Script (étape 2) — relu : facts.md, brief.md, style.md

**Logline** : *Pour qui regarde, la page Yo se présente par ce dont elle est faite — et le compte est vite fait.*

## Voix off (voix de synthèse, sur les temps forts ; ≤ 7 mots par carte à l'écran)
| s | texte dit |
|---|---|
| 0,35 | « Yo. » |
| 2,3 | « Cette page est faite de presque rien. » |
| 7,3 | « Zéro bibliothèque. » |
| 12,6 | « Elle s'ouvre. Elle répond. » |
| 20,8 | « Dis salut. » |
Silence de musique d'environ 0,7 s juste avant « Dis salut. ».

## Scènes (outil : `html` = moteur cinématographique ; toutes les scènes restent sur la page — voir la raison plus bas)
| # | s | Rôle dans l'histoire | Émotion | Preuve montrée | Durée | Outil |
|---|---|---|---|---|---|---|
| 1 | 0–2 | HOOK : « YO. » plein cadre sur le coup de grosse caisse | surprise, sourire | le mot-titre de la page | 2 s | html (texte cinétique, cercle ambre) |
| 2 | 2–4,5 | TENSION : « Cette page est faite de presque rien. » | curiosité | — (promesse à prouver) | 2,5 s | html (texte par lignes) |
| 3 | 4,5–7 | RÉVÉLATION 1 : le poids, compteur 0 → 5 424 octets | précision comique | taille réelle de `index.html` | 2,5 s | html (compteur) |
| 4 | 7–9 | PREUVE 1 : « 0 bibliothèque », « 0 requête externe » | netteté | 0 requête externe mesurée (Playwright) | 2 s | html |
| 5 | 9–12 | PREUVE 2 : la vraie page défile, gros plan sur les 3 cartes | « c'est réel » | les 3 vraies cartes, textes réels | 3 s | page (capture réelle, défilement + zoom) |
| 6 | 12–15,5 | PREUVE 3 : le formulaire se remplit et répond | satisfaction | réponse réelle « Merci Ana, message bien reçu (démo locale). » | 3,5 s | html (reconstitution fidèle du CSS/JS de la page, saisie animée) |
| 7 | 15,5–18,5 | « Pensée d'abord pour le mobile » : la vraie page mobile défile dans un téléphone | confiance | capture mobile réelle 390 px | 3 s | page en cadre téléphone |
| 8 | 18,5–20,5 | BILAN : « 1 fichier · 0 bibliothèque · 3 cartes · 1 formulaire » claqué sur le tempo | clarté | les 4 chiffres vérifiés | 2 s | html |
| 9 | 20,5–24 | APPEL À L'ACTION : « Dis salut. » + adresse | invitation | adresse de déploiement | 3,5 s | html |

**Pourquoi tout reste sur la page (pas de 3D, pas de footage, pas de générée)** : la création est une page plate sans objet ni lieu ; un téléphone 3D (Blender, `kit.phone`) aurait demandé l'installation de bpy (400 Mo) et ~10 à 25 s par image CPU pour un gain faible sur un sujet qui est *du texte et des cartes*. Les captures réelles de la vraie page portent la preuve. Choix, pas omission. La scène 6 est une **reconstitution** (pas un enregistrement) de ce que fait le formulaire ; la scène 1 et les compteurs sont du graphisme.
Aucune scène sans rôle.
