## demo setup

This is the setup of https://datasette-auth-osm-demo.fly.dev/

### deployment

deployed to fly.io

needs Client ID and Client Secret from https://www.openstreetmap.org/oauth2/applications/

```
fly launch
fly secrets set OSM_CLIENT_ID=xxx OSM_CLIENT_SECRET=xxx
fly deploy
fly scale count 1
```
