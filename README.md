## To start swagger ui with multiple documentation files copy the command below on your terminal
```bash
URLS=`cat $(pwd)/urls.json` \
export URLS && \
docker-compose up -d swaggerui
```