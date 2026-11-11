Structure des dossiers selon le cahier de charge:
docs/ : contient note de cadrage, MCD/MLD, schemas d'architecture
raw/2026-11-11: transfer du kit de donnees et des reponses JSON des API
sql/: 
   - 01_stg/
     --> Scripts de création et de bulk insert de la zone staging
   - 02_ods/
     --> Scripts du modèle 3NF, contraintes et procédures de nettoyage
   - 03_dw/
     --> Scripts de l'entrepôt en étoile (faits &amp; dimensions)
   - 04_securite/ 
     --> Scripts des rôles, Row-Level Security et Dynamic Data Masking
app/ : (reconsidere) code source de l'application full-stack
.gitignore : pour eviter d'envoyer des fichiers temporaires ou sensibles