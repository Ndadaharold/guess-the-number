documentation complète pour créer un jeu “Guess the Number” (Devine le nombre), en HTML, CSS et JavaScript , avec toutes les étapes pour :
	1.	Développer le jeu
	2.	Le publier sur GitHub avec GitHub Pages

⸻

1. Jeu “Guess the Number” – Objectif et fonctionnement

But du jeu :

L’utilisateur doit deviner un nombre généré aléatoirement par le programme. À chaque tentative :
	•	Le jeu lui dit si le nombre est trop bas, trop haut, ou correct.
	•	L’utilisateur a un nombre limité d’essais.
	•	Possibilité de rejouer à la fin.

⸻

2. Structure du projet (fichiers à créer)

Fichiers :
	•	index.html → structure de l’interface du jeu
	•	style.css → design visuel du jeu
	•	script.js → logique du jeu

⸻

3. Fonctionnalités principales à développer

A. HTML (structure)
	•	Champ de saisie (input) pour entrer un nombre
	•	Bouton de validation (“Deviner”)
	•	Zone de messages (indice, score, état du jeu)
	•	Bouton de reset (“Rejouer”)

B. CSS (design)
	•	Style simple et propre, responsive
	•	Couleurs changeantes selon les états (gagné/perdu)
	•	Effets visuels sur les boutons, champs, messages

C. JavaScript (logique du jeu)
	•	Générer un nombre aléatoire au démarrage
	•	Récupérer la valeur entrée par l’utilisateur
	•	Comparer la valeur avec le nombre cible
	•	Afficher des messages : “Trop haut”, “Trop bas”, “Correct !”
	•	Compter les tentatives restantes
	•	Gérer les cas de victoire ou de défaite
	•	Bouton pour redémarrer une nouvelle partie

⸻

4. Fonctionnalités bonus possibles
	•	Ajouter un score (meilleur score)
	•	Mode sombre/clair
	•	Sons ou animations en cas de victoire/défaite
	•	Limite de temps (chronomètre)
	•	Interface animée avec transitions CSS

⸻

5. Publier le projet sur GitHub avec GitHub Pages

Étape 1 : Créer un compte GitHub (si ce n’est pas déjà fait)
	•	https://github.com

⸻

Étape 2 : Créer un nouveau dépôt
	•	Nom : guess-the-number (par exemple)
	•	Optionnel : ajouter un README
	•	Crée le repo

⸻

Étape 3 : Préparer ton projet localement
	•	Crée un dossier avec tes trois fichiers (index.html, style.css, script.js)
	•	Vérifie que le projet fonctionne en local dans le navigateur

⸻

Étape 4 : Pousser sur GitHub

Méthode 1 : GitHub Desktop
	•	Ouvre GitHub Desktop
	•	“Add local repository”
	•	Sélectionne ton dossier
	•	“Publish repository”

Méthode 2 : Git en ligne de commande

cd ton-dossier
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/ton-utilisateur/guess-the-number.git
git push -u origin main



⸻

Étape 5 : Activer GitHub Pages
	•	Va sur ton dépôt en ligne
	•	Onglet Settings > Pages
	•	Source : branche main, dossier /root
	•	Clique sur Save
	•	Ton jeu sera en ligne à l’adresse :

https://ton-utilisateur.github.io/guess-the-number/



⸻

6. Astuce finale

Tu peux ensuite :
	•	Ajouter ton projet dans un portfolio web
	•	Partager le lien dans ton CV ou LinkedIn
	•	Ajouter une petite animation d’intro (CSS/JS)
