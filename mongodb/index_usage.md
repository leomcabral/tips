# Index Usage
#mongodb

## Query
```javascript
var collection = "metadata-dataset-splits";
db.getCollection(collection).aggregate({$indexStats:{}});
```

