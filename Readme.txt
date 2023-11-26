https://www.mongodb.com/docs/manual/tutorial/install-mongodb-on-os-x/#std-label-install-mdb-community-macos

The installation includes the following binaries:

The mongod server

The mongos sharded cluster query router

The MongoDB Shell,
mongosh

brew services start mongodb/brew/mongodb-community
brew services stop mongodb-community@7.0

brew services list

connect using
mongosh

show dbs
db.products.insertOne({name: "Max", age: 29, price: 12.99})
db.products.find()
db.products.find().pretty()