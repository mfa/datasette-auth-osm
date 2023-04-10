## demo setup

This is the exact setup of https://datasette-auth-osm.madflex.de

### run

```
touch empty.db
datasette publish cloudrun empty.db \
--install datasette-auth-osm \
--install datasette-block-robots \
--plugin-secret datasette-auth-osm client_id "your-client-id" \
--plugin-secret datasette-auth-osm client_secret "your-client-secret" \
--service datasette-auth-osm-demo
```
