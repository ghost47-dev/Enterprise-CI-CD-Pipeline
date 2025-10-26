# Enterprise CI/CD Pipeline (Python + GitHub Actions)

## Objectif
Automatiser le build et les tests d'une application Python via un pipeline CI/CD.

## Contenu
- Application Flask
- Tests unitaires Pytest
- Pipeline GitHub Actions

## Structure:
```
Enterprise-CI-CD-Pipeline/
│
├── app/
│   ├── __init__.py
│   └── app.py
│
├── tests/
│   └── test_app.py
│
├── docs/
│   ├── captures/
│   ├── description.md
│   ├── repartition_taches.md
│   ├── outils.md
│   └── logs.md
│   
│
├── .github/
│   └── workflows/
│       └── ci.yml
│
├── requirements.txt
└── README.md
```

## Exécution locale

### Installer les dépendances
`pip install -r requirements.txt`

### Lancer l'application
`python app/app.py`

### Lancer les tests
`pytest`
