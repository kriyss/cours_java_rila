# cours_java_rila

Repo Git : https://github.com/kriyss/cours_java_rila


## Banque

-  Créer un compte 
-  Consulter son compte
-  Faire un dépot 
-  Faire un retrait
-  faire un virement
-  Faire un crédit
-  Calcul AGIO
-  Taxe sur opération

## Technologie

- REST 
- Sans Framework 
- Servlet
- BDD : mongo / sql(jdbc)


### REST 

- POST /api/accounts/ -> id
- GET /api/accounts/ -> tous les accounts
- GET /api/accounts/{id} -> un seul compte
- DELETE /api/accounts/{id}

#### example 
- POST /api/accounts/ 
    {
        "name" : "ubisoft",
        "solde" : 150_000_000
    }


