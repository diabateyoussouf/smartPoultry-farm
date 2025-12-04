### smartPoultry-farm
    Description
    
    Service backend pour gérer les troupeaux de poulets dans une ferme avicole.
    Il permet de suivre :
    
    Les poulaillers (Barns)
    
    Les troupeaux (Flocks) : nombre de poulets, âge, santé, production d’œufs
    
    Organisation des troupeaux par bâtiments
    
    Ce service est un microservice Spring Boot et communique avec le service d’authentification pour sécuriser les endpoints via JWT.

###  Fonctionnalités principales

    Gestion des Barns (poulaillers)
    
    Gestion des Flocks (troupeaux)
    
    Suivi du nombre de poulets, âge moyen, santé globale et production d’œufs

    Sécurisation des endpoints via JWT fourni par le service auth-service
    
    Structure prête pour un futur dashboard et modèles IA
###  Les endpoints
`
GET /barns             -> Liste des poulaillers
GET /barns/{id}        -> Détails d’un poulailler
POST /barns            -> Créer un poulailler
PUT /barns/{id}        -> Modifier un poulailler
DELETE /barns/{id}     -> Supprimer un poulailler
`
