# LAN Live : application d'interaction (jeu 22)

© 2026 SAS BELM DEVELOPPEMENT. Tous droits réservés.

Pages : `joueur.html`, `enseignant.html` (tour de contrôle, protégée par un code), `classement.html` (écran projeté).
Publier avec GitHub Pages (branche main, racine).

## Version v14 (deck 357 diapos)

- 144 questions numérotées 1 à 144, dont 6 questions « nuage de mots » (3 mots par étudiant, 50 points par mot attendu trouvé, synonymes acceptés, masquage et fusion de mots par l'enseignant, nuage en direct sur l'écran projeté).
- Nouvelle question sur l'injection LDAP (remplace la question sur le RDN).
- Diapo de réponse associée à chaque question : arriver dessus corrige automatiquement la question en cours (mode automatique).
- Lien depuis le PowerPoint vers `classement.html` sans paramètre : rouvre la dernière séance lancée sur ce navigateur.

## Version v16 (deck 456 diapos)
- Numéros de pages mis à jour (deux pages de cours LDAP ajoutées avant la question 65) ; aucune question ajoutée ni renumérotée.
- Les « Séries » et exercices en groupe du cours deviennent des exercices individuels (sans numéro de série dans le deck).

## Version v15 (deck 454 diapos)

- Le PowerPoint pilote les écrans : page de question = question ouverte ; page suivante (réponse) = clôture et correction envoyée aux joueurs. Commandes manuelles réservées au « Mode secours ».
- Drapeau « ⚑ tous ont répondu » sur la tour de contrôle et sur l'écran projeté ; la fin du chrono ne ferme plus la question.
- « Question N » (numéro du PowerPoint) affiché partout ; correction détaillée (démarche, pourquoi pas les autres, rôle, pilotage) sur la tour ; démarche et rôle sur l'écran joueur.
- Adresse joueur fixe : `joueur.html` sans paramètre ouvre la séance du cours (séance « réelle » à adresse fixe) ; `classement.html` sans paramètre ouvre la dernière séance (ou celle du cours).
