# Simulateur de Location Multi-Appartements

🔗 [Voir le simulateur en ligne](https://lejrimostfa.github.io/airbnb_simulator/SimLoca.html)


Un simulateur interactif de revenus, dépenses et profits pour des appartements loués (Airbnb, etc.), avec :

- Configuration de plusieurs appartements  
- Tarifs journaliers ajustables via sliders  
- Dates d’introduction via calendrier et sliders relatifs  
- Facteur d’amplitude de la sinusoïde d’occupation  
- Graphique financier mensuel & cumulatif  
- Graphique annuel du taux d’occupation (en %)  
- Dark Mode avec palette néon cyberpunk  
- Export CSV & impression intégrés  

## Installation

1. Clonez ce dépôt :  
   ```bash
   git clone https://github.com/lejrimostfa/airbnb-simulator.git
   cd airbnb-simulator

	2.	Ouvrez simulateur.html dans votre navigateur moderne (Chrome, Firefox, Edge).
Aucun serveur ni dépendance n’est nécessaire.

Usage
	•	Durée simulation : glisser pour 1–10 années
	•	Tarif/jour : sliders 0–1000 € par appartement, pas de 5 €
	•	Date d’introduction : calendrier pour le premier, sliders relatifs pour les suivants
	•	Amplitude d’occupation : ajustez la saisonnalité
	•	Dark Mode : bouton en haut à droite
	•	Export CSV et Print : boutons en haut à gauche

Les graphiques se mettent à jour automatiquement 1 s après toute modification.

Structure
	•	simulateur.html : page unique HTML/CSS/JS
	•	Aucun build, tout est front-end pur

Contribuer
	1.	Fork ce projet
	2.	Créez une branche pour votre fonctionnalité :

git checkout -b feature/ma-fonctionnalite


	3.	Commitez vos changements, poussez et ouvrez une Pull Request.

⸻

Licence
Ce projet est distribué sous la licence MIT (voir fichier LICENSE).

---
