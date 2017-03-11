# Mongo

## get all index
db.getCollectionNames().forEach(function(collection) {    indexes = db[collection].getIndexes();    print("Indexes for " + collection + ":");    printjson(indexes); });

## get current operation
db.currentOp()

## get index from collections
db.product.getIndexes()

## create index
db.product.createIndex({"store" : 1,"is_deleted" : 1, "first_related" : 1, "published" : 1, "​likes":-1, categories:1})