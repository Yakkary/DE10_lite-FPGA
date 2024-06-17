# DE10_lite-FPGA

de10_lite_involved_projects
Ce dépôt contient une collection de projets basés sur VHDL, conçus pour le kit de développement FPGA DE10-Lite. Chaque projet exploite les capacités du FPGA Intel MAX 10, démontrant divers aspects de la conception numérique et du développement de systèmes embarqués. Le dépôt sert de ressource pour l'apprentissage, l'expérimentation et la mise en œuvre pratique de projets VHDL sur la plateforme DE10-Lite.

Structure du dépôt
README.md: Vue d'ensemble et instructions pour le dépôt.
/projects: Répertoire contenant les dossiers de projets individuels.
/nom_du_projet: Dossier de projet spécifique contenant tous les fichiers et la documentation pertinents.
/src: Fichiers source VHDL.
/sim: Fichiers de simulation et bancs de test.
/docs: Documentation, y compris les descriptions de projets, les instructions de configuration et les guides d'utilisation.
/constraints: Assignations de broches et fichiers de contraintes.
/build: Scripts et fichiers pour construire le projet.
/scripts: Scripts utilitaires pour la construction, la simulation et le déploiement des projets.
/docs: Documentation générale pour le dépôt, y compris des guides de configuration et des tutoriels.
/tools: Outils et utilitaires personnalisés pour le développement et le déploiement de projets.

Projets en vedette

#Horloge numérique avec 3 modes

Description: Une horloge numérique avec trois modes : chronomètre (montant), chronomètre (descendant) et configuration.
Concepts clés: Comptage, gestion du temps, et configuration d'interfaces utilisateur.
Usage: Démontre les concepts fondamentaux de la gestion du temps et de l'interaction utilisateur sur FPGA.

![image](https://github.com/Yakkary/DE10_lite-FPGA/assets/91556921/3d3d82cb-5700-48d6-8850-6d72bd8337a7)





#PWM pour contrôler l'intensité d'une LED

Description: Génère des signaux PWM pour contrôler l'intensité d'une LED en ajustant le cycle de service et le préscaler.
Concepts clés: Contrôle de cycle de service, génération de signaux haute fréquence, et techniques de modulation.
Usage: Illustre les applications pratiques de la modulation de signal pour le contrôle matériel.



#Jeu vidéo d'évitement d'obstacles

Description: Un jeu vidéo où le joueur doit éviter des obstacles qui apparaissent à l'écran.
Concepts clés: Génération de graphiques, gestion des entrées utilisateur, et logique de jeu en temps réel.
Usage: Fournit des insights sur la conception et la mise en œuvre de jeux vidéo simples sur FPGA.
Pour commencer


Cloner le dépôt:

bash
Copy code
git clone https://github.com/votrenomutilisateur/de10_lite_involved_projects.git
cd de10_lite_involved_projects
Configurer votre environnement de développement:

Installez le logiciel Intel Quartus Prime Lite Edition.
Assurez-vous d'avoir les pilotes et outils nécessaires pour la carte DE10-Lite.


Explorer et construire les projets:

Naviguez vers le répertoire du projet de votre choix.
Suivez les instructions dans le fichier README.md de chaque projet pour construire et déployer le design.
Contribuer
Les contributions sont les bienvenues! Veuillez soumettre des problèmes pour les bugs et les demandes de fonctionnalités, et n'hésitez pas à forker le dépôt et soumettre des pull requests.
