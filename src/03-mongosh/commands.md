## Connect to container
```sh
docker-compose exec mongodb bash
```

# Connect with mongosh
## Local
```sh
mongosh "mongodb://root:123456789@localhost:27017/?authMechanism=DEFAULT&tls=false"
```
## Atlas
```sh
mongodb+srv://cesarfigue06:123456789@mongodbseom.mxclroj.mongodb.net/test
```

## Show db
```ssh
show collections
```

## Select Db
```ssh
use("SeomStore")
```
## Show collections
```ssh
show collections
```

## Show collection
```ssh
db.Products.find()
```