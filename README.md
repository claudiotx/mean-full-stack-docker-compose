# MEAN Stack Docker Boilerplate
This stack boilerplate is powered by Docker Compose.
Do not use JavaScript.
This boilerplate is opinionated towards the usage of TypeScript over vanilla JavaScript.
This is work in progress.

## TODO
Swap Docker Compose with MiniKube

## TLDR
Build the frontend dist files `ng build --prod`, then:
`./start-cluster.sh`
Frontend: `curl http://localhost`
Backend: `curl http://localhost:3600`
`CTRL+C` do take down the cluster.


## Components
- Frontend: Angular (ws by NGiNX)
- Backend: ExpressJS
- Database: MongoDB
- Mem Cache: Redis

## Frontend
`cd frontend`
`npm install`
`ng serve`
`ng build --prod`
docker 
## Code from inside a container
`docker-compose exec backend bash`.

## Powered by
https://www.coderecipes.org