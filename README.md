# TP 24 : Conteneurisation Spring Angular avec Docker et Docker Compose

---

## 1. Clonage et organisation de la structure du projet SmartHouse (Smart_Home_back & smartHome-front)

![1. Clonage et organisation de la structure du projet SmartHouse](screenshots/01_git_clone_project_structure.png)

---

## 2. Compilation et packaging Maven du backend Spring Boot (mvn clean package -DskipTests)

![2. Compilation et packaging Maven du backend Spring Boot](screenshots/02_backend_maven_clean_package.png)

---

## 3. Configuration du Dockerfile Backend multi-stage (Smart_Home_back/Dockerfile)

![3. Configuration du Dockerfile Backend multi-stage](screenshots/03_dockerfile_backend.png)

---

## 4. Configuration du Dockerfile Frontend Angular multi-stage avec Nginx (smartHome-front/Dockerfile)

![4. Configuration du Dockerfile Frontend Angular multi-stage avec Nginx](screenshots/04_dockerfile_frontend.png)

---

## 5. Configuration du fichier d'orchestration multi-conteneurs (docker-compose.yml)

![5. Configuration du fichier d'orchestration multi-conteneurs](screenshots/05_docker_compose_configuration.png)

---

## 6. Construction des images Docker avec Docker Compose (docker-compose build)

![6. Construction des images Docker avec Docker Compose](screenshots/06_docker_compose_build.png)

---

## 7. Démarrage des conteneurs orchestrés en arrière-plan (docker-compose up -d)

![7. Démarrage des conteneurs orchestrés en arrière-plan](screenshots/07_docker_compose_up.png)

---

## 8. Vérification de l'état des conteneurs actifs (docker-compose ps)

![8. Vérification de l'état des conteneurs actifs](screenshots/08_docker_compose_ps.png)

---

## 9. Consultation des logs du conteneur Backend Spring Boot (docker-compose logs backend)

![9. Consultation des logs du conteneur Backend Spring Boot](screenshots/09_docker_compose_logs_backend.png)

---

## 10. Consultation des logs du conteneur de base de données MySQL (docker-compose logs mysql)

![10. Consultation des logs du conteneur de base de données MySQL](screenshots/10_docker_compose_logs_mysql.png)

---

## 11. Test d'accès à l'API REST Backend Spring Boot (GET http://localhost:8085/api/appareils)

![11. Test d'accès à l'API REST Backend Spring Boot](screenshots/11_test_backend_api.png)

---

## 12. Test d'accès au Frontend Angular hébergé sur Nginx (GET http://localhost:80)

![12. Test d'accès au Frontend Angular hébergé sur Nginx](screenshots/12_test_frontend_nginx.png)

---

## 13. Test d'accès à l'interface d'administration PhpMyAdmin (GET http://localhost:8081)

![13. Test d'accès à l'interface d'administration PhpMyAdmin](screenshots/13_test_phpmyadmin_http.png)
