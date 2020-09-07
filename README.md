# nodejsexpenses
Connect to mongo container user portainer or other means

mongo --username xxx --password xxx

use Expenses

db.createUser({user:"xxx",pwd:"xxx",roles:[{role: "readWrite" , db:"Expenses"}]},{w:"majority",wtimeout:5000})

