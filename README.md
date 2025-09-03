🚀 Katalon Studio – API Test Automation (REST + SOAP)












Framework d’automatisation complet avec Katalon Studio
Inclut REST API Testing + SOAP API Testing, exécutions Data-Driven, intégration CI/CD et rapports avancés.

📋 Table des matières

🔧 Installation

▶️ Exécution des tests

📂 Structure du projet

✅ Scénarios testés

📊 Rapports & Intégration

🔄 CI/CD intégré

🤝 Contribuer

📄 Licence

🔗 Contact & LinkedIn

📂 Structure du projet
├── Test Cases/                 # Cas de test API (REST + SOAP)
├── Test Suites/                # Groupes de tests organisés
├── Data Files/                 # Données de test (CSV/Excel)
├── Object Repository/          # Endpoints REST + Services SOAP
├── Profiles/                   # Variables globales
├── Include/                    # Configurations utilitaires
├── Reports/                    # Rapports générés
├── Jenkinsfile                 # Pipeline CI/CD
└── README.md                   # Documentation du projet

✅ Scénarios testés
Module/API	Description
REST Auth	Authentification (Basic, Bearer, OAuth)
REST CRUD	Création / Lecture / Mise à jour / Suppression (Users)
SOAP Demo	AddInteger, FindPerson, LookupCity, QueryByName…
SOAP Pays	CapitalCity, Currency, CountryInfo, Langues, Drapeaux
Data-Driven	Exécution paramétrée via CSV/Excel
Chaining	Réutilisation de réponses JSON/XML dans d’autres tests
📊 Rapports & Intégration

📑 Rapports JUnit / HTML / CSV / PDF

📈 Katalon TestOps pour dashboards & analytics

📸 Logs & screenshots en cas d’échec

🔍 Intégration possible avec Allure Report

🔄 CI/CD intégré
✅ GitHub Actions

Exécution des suites REST & SOAP en pipeline

Génération & upload des rapports

Fichier : .github/workflows/katalon.yml

✅ Jenkins

Pipeline CI/CD avec Jenkinsfile

Étapes principales :

Clone du repo

katalonc -testSuitePath="..."

Génération des rapports

Archivage logs/screenshots

📄 Licence

Projet sous licence MIT.
Voir LICENSE
 pour plus de détails.

🔗 Contact & LinkedIn

👤 Abdelhakim SAHRAOUI

📧 hakim.sahraoui.de@gmail.com
