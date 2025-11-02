# 🧠 Gestion Informatique — Inventaire & Support Technique

Ce dépôt regroupe deux volets essentiels de la gestion IT :
1. **Inventaire du parc informatique** (matériel, logiciels, licences)
2. **Suivi des tickets d’incidents** (diagnostics, actions correctives, performances)

## 📁 Contenu du dépôt

- `inventaire_informatique.csv` : Liste complète des équipements et logiciels
- `ticket.xlsx` : Historique des demandes d’assistance technique
- `images/` : Captures d’écran des interfaces de suivi (GLPI, tableur, Jira)
- `README.md` : Documentation du projet

---

## 🗂️ Inventaire Informatique

Le fichier `inventaire_informatique.csv` contient :

- **Équipements** : PC, serveurs, imprimantes, téléphones IP, tablettes, moniteurs
- **Logiciels** : Windows, Office 365, Sage, Adobe, etc.
- **Colonnes clés** :
  - ID actif, Type, Marque/Modèle, Numéro de série
  - Utilisateur, Localisation, Date d’achat, Fin de garantie
  - Logiciels installés, Licence, Fournisseur, Statut
  - Commentaires, Problèmes/Solutions

🔍 **Objectifs** :
- Suivre les garanties et les licences
- Identifier les équipements fictifs ou non conformes
- Filtrer par localisation, utilisateur ou type

📌 **Utilisation** :
- Ouvrir dans Excel (UTF-8)
- Appliquer des filtres pour audits ou maintenance
- Exporter en PDF ou intégrer dans GLPI

---

## 🧾 Suivi des Tickets IT

Le fichier `ticket.xlsx` documente les interventions techniques :

- **Colonnes clés** :
  - ID du ticket, Date, Demandeur, Service concerné
  - Description, Gravité, Diagnostic, Action corrective
  - Durée de résolution, Technicien, Statut, Commentaire

🛠️ **Exemples** :
- T003 : Problème Outlook — cache corrompu, résolu en 20 min
- T004 : Erreur au démarrage — restauration système, résolu en 45 min

🎯 **Objectifs** :
- Centraliser les incidents
- Documenter les solutions
- Suivre les performances des techniciens
- Identifier les zones sensibles ou récurrentes

📌 **Utilisation** :
- Filtrer par gravité, statut ou service
- Exporter pour reporting ou archivage

---
