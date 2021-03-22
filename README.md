## Docker-compose build for RESTful client

### includes services
1. frontend - react js
2. back end - nest js
3. server - nginx


### run in production mode 
`docker-compose up -d`
### run in development mode
`docker-compose -f docker-compose.yml -f docker-compose.development.yml up -d`