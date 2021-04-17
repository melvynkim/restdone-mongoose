[![NPM](https://nodei.co/npm/restdone-mongoose.png?compact=true)](https://npmjs.org/package/restdone-mongoose)

Mongoose Data Source for Restdone
==========

Restdone - simplify RESTful service

https://github.com/melvynkim/restdone


# Usage Example

```
  MongooseDataSource = require('restdone-mongoose'),
  User = require('mongoose').model('User'),

...

module.exports = BaseController.extend({
  dataSource: new MongooseDataSource(User),
...

```


# Issues

https://github.com/melvynkim/restdone-mongoose/issues