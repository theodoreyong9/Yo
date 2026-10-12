# Faits (étape 0) — format 1:1

## Ce que ma création est (lu dans `index.html`, ouvert dans Chromium)
- Une page web d'un seul fichier : `index.html`, **5 424 octets (≈ 5 Ko)**.
- **Aucune requête externe** : aucun script, feuille de style, police ou image chargés depuis un autre site (les seuls « http » du fichier sont l'espace de noms d'une icône SVG intégrée). Vérifié : 0 requête échouée, 0 erreur console, 0 réponse ≥ 400 dans Playwright.
- Contenu réel : un en-tête « YO » avec 2 liens (À propos, Contact) ; un titre « Salut, je suis Yo. » ; la phrase « Une page web simple, sobre et rapide : un seul fichier, aucune dépendance, lisible partout. » ; un bouton « Découvrir » ; **3 cartes** (01 Simple : « Un seul fichier HTML, sans bibliothèque ni outil de build. » / 02 Adaptable : « Pensée d'abord pour le mobile, elle s'étend proprement sur grand écran. » / 03 Accessible : « Contrastes élevés, navigation au clavier et respect des animations réduites. ») ; **1 formulaire** (Nom, Message, Envoyer) qui répond « Merci <nom>, message bien reçu (démo locale). » ou « Merci de remplir les deux champs. » — il n'envoie rien : démo locale.
- Palette de la page : fond #0b0b0f, texte #f2f0ea, ambre #ffb347 ; police système (rendue en Inter ici).
- Adresse publiée : https://theodoreyong9.github.io/Yo/ (déploiement réussi depuis `main`, run n° 8 ; adresse non joignable depuis cet environnement, donc non contrôlée en direct).

## Captures réelles (Chromium, Playwright)
`aiwa-videos/media/` : hero-desktop, about-desktop, contact-desktop (1440×810) ; m-hero, m-about, m-contact (390×780, ×3). Page entière : `square/page-full.png` (capture `video-kit capture`).

## Ce qui vient de moi (ajout, pas un fait de la page)
Le cadrage « une page faite de presque rien » est un parti pris de mise en scène, bâti sur des chiffres vrais ci-dessus. Voix et musique : voir `brief.md`.

## Ce qui n'est PAS établi (donc absent du film)
Aucun nombre de visiteurs, aucune comparaison avec d'autres pages, aucune mesure de vitesse, aucun témoignage.
