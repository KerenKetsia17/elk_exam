# ELK Stock-MS

## Description
Mettre en place une stack ELK (Elasticsearch, Logstash, Kibana) pour la collecte, l'analyse et la visualisation des logs générés par l'application.

## Prérequis

- Docker et Docker Compose
- Elasticsearch
- Logstash
- Kibana

## Installation

### 1. Cloner le dépôt
Clonez le dépôt GitLab sur votre machine locale :
git clone https://gitlab.com/m2gl1/stock-ms.git
cd stock-ms


### 3. **Fichiers utilisés pour la mise en place de la stack ELK**

Voici la structure du projet et les fichiers associés à la mise en place de la stack ELK.

---

## Structure du projet

stock-ms/
├── docker-compose.yml        # Fichier de configuration Docker Compose pour déployer la stack ELK
├── logstash/
│   ├── config/
│   │   └── logstash.yml      # Configuration de Logstash
│   └── pipeline/
│       └── logstash.conf     # Pipeline Logstash pour l'ingestion des logs
└── src/
    └── ...                   # Code source de l'application de gestion des stocks
