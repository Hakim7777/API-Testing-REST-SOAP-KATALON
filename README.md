🚀 Katalon Studio – API Test Automation (REST + SOAP)

Framework d’automatisation complet avec Katalon Studio dédié aux tests API.
Inclut REST API Testing + SOAP API Testing, tests paramétrés (Data-Driven), intégration CI/CD et rapports avancés.

📋 Table des matières

🔧 Installation

▶️ Exécution des tests

📂 Structure du projet

✅ Cas de test & scénarios couverts

📊 Rapports & Intégration

🔄 CI/CD intégré

🤝 Contribuer

📄 Licence

🔗 Contact

📂 Structure du projet
├── Test Cases/                 # Cas de test API (REST + SOAP)
├── Test Suites/                # Groupes de tests organisés
├── Data Files/                 # Données (CSV/Excel) pour Data-Driven
├── Object Repository/          # Objets REST & SOAP (endpoints, services…)
├── Include/                    # Configs et utilitaires
├── Profiles/                   # Variables globales
├── Reports/                    # Rapports générés
├── Jenkinsfile                 # Pipeline CI/CD (optionnel)
└── README.md                   # Documentation

✅ Cas de test & scénarios couverts
Type	Description
REST API	Authentification (Basic, Bearer, OAuth), CRUD Users, Employees API
SOAP API	Services Pays (capitale, monnaie, langues, infos complètes) + SOAP Demo
Data-Driven	Exécution des mêmes tests via CSV/Excel
Vérifications	Status codes, response body JSON/XML, schémas et données dynamiques
Chaînage	Réutilisation de la réponse d’un appel comme input pour un autre
📊 Rapports & Intégration

📑 Rapports HTML / JUnit / CSV générés automatiquement

📈 Intégration avec Katalon TestOps pour dashboards & analytics

📸 Screenshots/logs en cas d’échec

🔍 Compatible avec Allure Report

🔄 CI/CD intégré
GitHub Actions

Exécution des suites en pipeline

Génération & upload des rapports

Jenkins

Pipeline CI/CD avec Jenkinsfile

Étapes principales :

Clone du repo

katalonc -testSuitePath="..."

Génération des rapports

Archivage logs/screenshots

📄 Licence

Projet sous licence MIT – voir LICENSE
.

🔗 Contact

👤 Abdelhakim SAHRAOUI
📧 hakim.sahraoui.de@gmail.com

🔗 LinkedIn
