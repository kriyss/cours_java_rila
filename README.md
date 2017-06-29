# cours_java_rila

mail : `kriyssou@gmail.com`

## Repo Git 

- cours : [https://github.com/kriyss/cours_java_rila](https://github.com/kriyss/cours_java_rila)
- damien / bjorn : [https://gitlab.com/BetIzy/Daks.git](https://gitlab.com/BetIzy/Daks.git)
- [https://bitbucket.org/MicroCheapFx/bankybanky](https://bitbucket.org/MicroCheapFx/bankybanky)

example d'api rest : (paypal)[https://developer.paypal.com/docs/api/payments/#payment_list] 

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
        "name" : "lubrisoft",
        "solde" : 150_000_000
    }



### Exemple d'entité

- Compte bancaire : 
    numero de compte
    nom
    solde
    utilisateur[]
    option[]




## 

