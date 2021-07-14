# README
Cette application responsable du traitement des PVs.
Elle a été réalisé lors de mon stage au Département de Mathématiques de l'Université Paul Sabatier dans le cadre d'un stage lors de ma L3 SID

## Comment l'utiliser


0. Télécharger l'application et installer toutes les dépendances
1. Placer les PVs (au format pdf) à traiter dans le dossier **Fichiers_pdf_input**
2. Lancer le script **run_app.sh** à partir d'un terminal.
3. Attendre que l'ensemble des fichiers soient traiter (cela peut prendre plusieurs minutes)
4. Attendre la génération des fichiers responsable du suivi étudiants (cela prend quelque secondes)
5. (Pas encore implémenté) attendre que le tableau de bord se lance.

### Notes
* Le fichier **logfile.txt** détaille le déroulement de l'exécution de l'application
* Le dossier **Fichier_pdf_erreur** receuille les PVs qui ont eu un problème lors de l'exécution (si c'est un scan par exemple)
* Le dossier **Fichier_pdf_traites** receuille les PVs qui n'ont PAS eu de problème à l'exécution
