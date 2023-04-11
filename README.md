# Template Node (BackEnd)

- install dependencies

        npm i

- Run as Production Server

        npm run prod

- Run as Development Server

        npm run dev

- add the config file in your .gitignore
- customize the models, routes, controllers

## person resource

### method type : post

    http://localhost:5000/person

    {
    "name": "name",
    "email": "email@gmail.com",
    "number": "+9231312121",
    "city" : "ABC"

    }

### method type : Get

    http://localhost:5000/person

### method type : put

    http://localhost:5000/person

    {
    "name2": "updated Name"
    "name": "name",
    "email": "email@gmail.com",
    "number": "+9231312121",
    "city" : "ABC"

    }

### method type : delete

    http://localhost:5000/person/name
