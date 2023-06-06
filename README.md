# Rest-API-For-NFT
To build the Rest-API for NFT Marketplace using NodeJs and MongoDB.
```shell
$ npm init 
$ npm i express@4 
$ sudo npm install -g nodemon 
```

```shell
* JSON.parse() method used to convert the json file to object
* get status: 200
* post status: 201
```

```shell
* Express Middleware :- Which allow us to read the data from the user and write our document.
  app.use(express.json());
```
```shell
//to convert the id into int
  const id=parseInt(req.params.id);
  or
  const id= req.params.id *1; 
```

```shell
patch method :- Update the only desired value from the database.
put method :- Update the whole database 
```
