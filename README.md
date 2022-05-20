# Template Node (BackEnd)

- add the config file in your .gitignore
- customize the models, routes, controllers accordingly

## create person resource

### method type : post

    http://localhost:4000/person
    
    { 
    "name": "name",
    "email": "email@gmail.com",
    "number": "03003456505",
    "city" : "sukuer"
    
    }

### method type : Get 
    http://localhost:4000/person


### method type : put

    http://localhost:4000/person
    
    { 
    "name2": "updated Name"
    "name": "name",
    "email": "email@gmail.com",
    "number": "03003456505",
    "city" : "sukuer"
    
    }
### method type : delete

    http://localhost:4000/person/name
### method type : delete

    http://localhost:4000/personByName/name

### creted for Dot-project