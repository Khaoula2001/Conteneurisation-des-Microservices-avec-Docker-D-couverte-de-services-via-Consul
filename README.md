# TP 25 : Conteneurisation des Microservices avec Docker + Découverte de services via Consul

## Objectifs
Orchestration de microservices Spring Boot avec Docker et Consul.

## Architecture
- **Services** : Client, Voiture, Gateway, Consul, MySQL, phpMyAdmin.
- **Réseau** : Bridge unique.

## Déroulement

### 1. Structure et Dockerfiles (17h31)
Création des Dockerfiles multi-stage.
![Structure](screens/2026-01-01_17h31_27.png)

### 2. Configuration (17h56)
Fichier `docker-compose.yml` finalisé.
![Compose](screens/2026-01-01_17h56_33.png)

### 3. Démarrage (18h06)
Build et lancement : `docker compose up -d --build`.
![Start](screens/2026-01-01_18h06_47.png)

### 4. Logs (18h07)
Vérification du démarrage correct.
![Logs](screens/2026-01-01_18h07_58.png)

### 5. Consul (18h09)
Services enregistrés avec succès.
![Consul](screens/2026-01-01_18h09_05.png)

### 6. Gateway (18h13)
Routage fonctionnel via le port 8888.
![Gateway](screens/2026-01-01_18h13_38.png)

### 7. BDD (18h21)
Bases créées visibles sur phpMyAdmin.
![BDD](screens/2026-01-01_18h21_51.png)

### 8. Validation (18h23)
Architecture complète opérationnelle.
![Validation](screens/2026-01-01_18h23_52.png)
