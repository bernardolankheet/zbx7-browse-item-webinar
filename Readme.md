## Install Docker
Install Docker using [get.docker.com](https://get.docker.com)

`
curl -fsSL https://get.docker.com -o install-docker.sh && sudo sh install-docker.sh
`

## Get docker compose File
Get docker-compose.yaml file and deploy.

## Deploy Stack
`
docker stack deploy -c docker-compose.yaml zbx-7
` 

## Trobleshooting


Check Running Containers:
`
docker ps
` 

Check images:
`
docker image ls
`

Check services with logs
`
docker stack ls
`
`
docker stack ps zbx-7 --no-trunc
`
Check container logs
`
docker ps
`
`
docker logs ID_CONTAINER
`

#exemplo
`
docker container logs 5a74f21c7f55
`

Remove Stack
`
docker stack rm zbx-7
`


## LAB
Importa os templates e posteriomente importe os host, utilize os arquivos .yaml com o nome de hosts no inicio.

