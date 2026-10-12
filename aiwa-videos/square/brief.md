# Brief (étape 1) — relu : facts.md

**Public** : quelqu'un qui fait défiler un fil carré (Instagram, LinkedIn) ; il doit comprendre en 3 s.
**UN message** : cette page tient en presque rien — et elle dit salut.
**Ton** : sec, malin, un sourire. Jamais de superlatif.
**Direction artistique** : prise dans la page — nuit #0b0b0f, ivoire #f2f0ea, ambre #ffb347 ; gros caractères noirs (Inter Display Black) ; compteurs en mono.
**Format / durée** : 1:1, 1080×1080, 19,8 s, MP4 H.264 + AAC.
**Appel à l'action** : « Dis salut. » + theodoreyong9.github.io/Yo.

## Stratégie (section 0 du guide)
1. **Contexte** : une petite page personnelle d'un fichier, trois cartes, un formulaire démo. Ce qu'elle n'est pas : un site vitrine complet, une appli, un produit mesuré.
2. **Tension (vraie, tirée des faits)** : une page qui se présente est vite faite — et c'est son sujet. La tension : « qu'est-ce qu'on peut raconter avec si peu ? » → on le dit en chiffres exacts, vite.
3. **Idées (8)**, notes /5 sur originalité · clarté 5 s · émotion · fit · faisable ici :
   a. La page se présente en listant ce dont elle est faite (« faite de : 1 fichier, 0 bibliothèque… ») — 5·5·3·5·5 = **23**
   b. Un salut qui attend une réponse (le film tape « Yo », la page répond) — 4·4·4·4·4 = 20
   c. Défilement continu de la vraie page, voix off — 2·4·2·5·5 = 18
   d. Une porte qui s'ouvre sur la page — 3·3·3·2·3 = 14
   e. Compte à rebours de poids (5 Ko) — 3·4·2·5·4 = 18
   f. Le formulaire comme dialogue (conversation) — 3·4·4·4·4 = 19
   g. Page 3D flottante rendue Blender — 4·3·3·3·1 = 14 (pas de GPU, trop lent pour la valeur)
   h. Avant/après vs une page « classique » — **écartée : inventerait une comparaison**.
   **Retenue : a** (la plus claire et la plus à elle), avec le geste de **b** en preuve (le formulaire répond). c, e, f perdent par manque de surprise ; d, g par coût sans gain ; h par honnêteté.
4. **Proposition** : *« Pour qui regarde, la page Yo se présente par ce dont elle est faite — et le compte est vite fait. »* À retenir : on peut lui dire salut.
5. **Pré-mortem** : (i) personne ne comprend les 3 premières secondes → « YO. » plein cadre sur le premier temps, puis la phrase « Cette page est faite de… » avant 3 s ; (ii) ressemble à toutes les vidéos produit → pas de capture centrée : la vraie page défile en gros plan, compteurs exacts ; (iii) la preuve n'est pas crédible → chaque chiffre est vérifiable (5 424 octets, 0 requête externe, 3 cartes, 1 formulaire), la réponse du formulaire est montrée telle quelle, « démo locale » inclus.

## Campagnes de référence (video-research, lues dans le catalogue)
- **adidas — « This Campaign is Made of Fenerbahçe »** (https://www.adsoftheworld.com/campaigns/this-campaign-is-made-of-fenerbahce) : je retiens la forme « c'est fait de… » comme moteur d'un film ; je n'en copie ni l'émotion collective ni rien d'autre.
- **Flipkart — « GenZ »** (https://www.adsoftheworld.com/campaigns/genz) : je retiens l'idée qu'une adresse web peut être la chute du film.
Aucun autre élément repris. (Les 8 résultats du catalogue sont des campagnes de marques sans lien avec une page personnelle ; seul l'angle d'écriture est utile.)

## Son
- **Musique** : la piste choisie dans le registre (« Brain Dance », Kevin MacLeod, incompetech, CC BY 4.0, 124 bpm) n'est **pas téléchargeable depuis cet environnement** (incompetech injoignable, copie du dépôt absente : 404). Repli demandé par le guide : **rythme généré `beat.py`**, ~120 bpm, accent sur chaque coupe. Aucun crédit à afficher. **Provisoire.**
- **Voix off** : voix neuronale Piper « siwis medium » via sherpa-onnx (installée par `voice-setup.sh`), seulement sur les temps forts. Provisoire (voix de synthèse).
