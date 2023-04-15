I was exploring few vector databases and first came across milvus and found working code for it in repo https://github.com/dshvimer/milvus-up-and-running. However, I was only able to make it work for older versions of milvus and connections with new version didnt work which led me towards exploring weaviate vector database.
In this repo, I have configured weaviate with similiar use-case, i.e to find similiar images by using vector similiarity search in weaviate. The vectors are computed using Resnet18

## Setup Instructions
1. Install [docker](https://docs.docker.com/get-docker/)
2. Run `docker-compose build` and then `docker-compose build` in the root directory
3. Open `http://127.0.0.1:8888/lab` on your browser and get the token (or full url with token) from the logs of notebook container by using below commands.    
Use `sudo docker ps` to list the running containers and get the container id for notebook container and then use  `sudo docker logs <container_id>`, you'll get the url and token at the bottom of logs.

