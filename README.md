## How to connect
Check the addresses assigned:
- The 10.112.x.y address is for connection from outside the bigdata platform
- The 10.117.x.y address is for connection from other bigdata node

To connect to the instance using the mongo CLI:

    mongo --host 10.112.x.y

You will start in the test database.

Example commands:
```
show dbs
db
use test
db.inventory.insert( { x: 1 } );
db.inventory.find()
```

Tutorial (for version 4.0, we have version 3.2):
- https://docs.mongodb.com/manual/tutorial/getting-started/
