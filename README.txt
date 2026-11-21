SDS3D — préparation locale de modèles STL

Contenu du dépôt GitHub Pages : index.html, engine.mjs, worker.js et manifold.wasm.

Fonctions : prévisualisation 3D, agrandissement, profils Bambu Lab H2S/P1S, découpe plane en grille adaptée au volume, évidement avec épaisseur réglable, orientation heuristique pour limiter les surplombs, tourillons et logements avec jeu réglable, export des pièces en STL et d’un plan JSON dans un ZIP.

Déploiement : déposer tous les fichiers de ce dossier à la racine du dépôt GitHub. Dans Settings > Pages, choisir Deploy from a branch, branche main, dossier /(root). Attendre la publication puis ouvrir l’URL Pages.

La scène 3D et les fichiers du modèle restent sur l’appareil. Three.js et deux bibliothèques géométriques sont chargés depuis jsDelivr; la première ouverture nécessite Internet. Les modèles doivent être des volumes fermés. La sélection d’orientation estime les surplombs, elle ne remplace pas la prévisualisation des supports dans Bambu Studio. Les surfaces découpées sont planes; les jonctions trop minces sont signalées.
