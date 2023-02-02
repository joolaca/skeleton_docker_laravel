## install docker
https://docs.docker.com/get-docker/

### clone https://github.com/joolaca/skeleton_docker_laravel.git

### rename .env_docker to .env

`docker-compose up -d`

### entering the docker environment

`docker-compose exec server bash`

### install laravel
`composer create-project --prefer-dist laravel/laravel:^8.0 laravel`
### Delete File
rm laravel/.env
rm laravel/readme.md

### Move File
mv laravel/* .

### Delete empty Project
rm -rf laravel

###  add permission to folder

sudo chmod -R 777 ./storage/*

## Page
http://localhost:8101/

## MySql admin
http://localhost:8102/
### user:  skeleton
### pass:  skeletonPass123!