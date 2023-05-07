# criar o projeto
    * npm init -y
# Dependências
    * npm install --save json-server

# Configurar o package.json
* package.json
    "start": "json-server --watch db.json --port 3001"

# EndPoint
    * get
        * http://localhost:3001/users
    * put
        http://localhost:3001/users/1
    * delete
        http://localhost:3001/users/1