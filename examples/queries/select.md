# `type: select` query example

``` js
var sql = jsonSql.build({
    type: 'select',
    table: 'table'
});
```

Result:

``` js
sql.query
// select * from "table";

sql.values
// {}
```