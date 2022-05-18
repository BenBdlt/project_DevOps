## Page GitHub - DevOps projet B3DEV - Benjamin Bordelet

### Liste des étapes de la pipeline réalisé sur GitHub :

```markdown
Test Unitaire :
- Build de l'applciation NodeJS
- Lancement du script de test (npm run test)
- 
Test de Sécurité :
- Build de l'image docker
- Scan de vulnérabilité Trivy
- 
Test de Qualité :
- Utilisation de Sonarcloud et son indice de qualité

Push de l'image Docker sur DockerHub :
- Connexion au DockerHub
- Connexion au registre des container
- Build & push de l'image Docker

Mise en place d'un artifact téléchargeable
- Créer un dossier downloads, disponible en bas de chaque actions de test GitHub
- Texte de confirmation du bon déroulement du script

Notification Discord
- Ajout d'un WebHook relié au salon travail d'un serveur discord personnel
- Notification sur le salon discord lors d'un push sur main
```
![image](https://user-images.githubusercontent.com/57449415/169058503-425a2d3a-4c31-4156-98b5-a32d1656c47c.png)
