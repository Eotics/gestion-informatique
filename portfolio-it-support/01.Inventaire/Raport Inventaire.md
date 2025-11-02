# 🗂️ Inventaire Informatique — Philippe Valentin

Ce fichier CSV contient l'inventaire détaillé du parc informatique de l'organisation, incluant les équipements, logiciels, utilisateurs, et informations de garantie.

## 📦 Contenu du fichier

Chaque ligne représente un actif informatique avec les colonnes suivantes :

- **ID actif** : Identifiant unique de l’équipement ou logiciel
- **Type d'équipement** : Ordinateur, serveur, imprimante, logiciel, etc.
- **Marque / Modèle** : Référence constructeur
- **Numéro de série** : Identifiant matériel
- **Utilisateur** : Personne ou service assigné
- **Localisation** : Bureau, étage, salle serveur…
- **Date d'achat** / **Fin de garantie**
- **Logiciels installés** : Liste des logiciels présents
- **Licence (Oui/Non)** : Statut de conformité
- **Fournisseur** : Origine de l’équipement
- **Statut** : Actif, hors service, etc.
- **Commentaire libre** : Notes techniques ou d’usage
- **Problèmes/Solution** : Historique ou recommandations

## ✅ Objectifs

- Assurer le suivi du matériel et des logiciels
- Vérifier la conformité des licences
- Identifier les équipements à surveiller ou remplacer
- Faciliter les audits et la maintenance

## 📊 Statistiques incluses

En bas du fichier, des lignes de synthèse indiquent :
- Nombre total d’équipements
- Répartition par type (PC, serveur, logiciel, etc.)
- Équipements fictifs ajoutés à des fins pédagogiques

## 🛠️ Utilisation recommandée

1. Ouvrir le fichier avec Excel ou un tableur compatible UTF-8
2. Appliquer des filtres sur les colonnes pour :
   - Identifier les licences expirées
   - Repérer les équipements hors garantie
   - Trier par localisation ou utilisateur
3. Exporter en PDF ou intégrer dans GLPI si nécessaire

## 📌 Notes

- Les équipements fictifs sont marqués pour usage pédagogique
- Certaines licences sont non conformes (⚠️ à corriger)
- Le fichier peut être enrichi avec des colonnes supplémentaires (coût, état, etc.)
