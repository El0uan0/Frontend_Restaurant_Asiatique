# Borne de Commande - Frontend JavaFX

Ce dépôt contient l'interface utilisateur (Frontend) pour la borne de commande de restauration asiatique.
Il s'agit d'une application de bureau développée en JavaFX qui communique avec l'API Backend.

## Auteurs (Groupe)
- Icham OULALI
- Pierre Michel NDENGUE BOUNOUNOU
- Ouday GDIRI
- Elouan QUENTEL

## Prérequis
- Java 17 (JDK)
- Maven 3.x
- Le **Backend** doit être lancé au préalable pour que l'application fonctionne correctement.

## Installation et Lancement

### 1. Cloner le projet
```bash
git clone <URL_DU_REPO_FRONTEND>
cd Frontend_Restaurant_Asiatique
```

### 2. Lancer l'application
Utilisez Maven pour nettoyer, compiler et démarrer l'interface :
```bash
mvn clean javafx:run
```

## Structure
- **Vue** : Fichiers FXML
- **Contrôleurs** : Gestion des interactions
- **Services** : Communication HTTP avec le Backend

## Note
Assurez-vous que le backend tourne sur `http://localhost:7000` avant de lancer le frontend.