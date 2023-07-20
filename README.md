##Customer Management Portal

This repo contains 2 submodules and this is done to start whole application 
in 1 go.

https://github.com/deejay6/quantaco_backend

https://github.com/deejay6/quantaco_ui 

## Steps to run this application

1. Clone this repo
   ``git clone https://github.com/deejay6/quantaco.git``
   
2. Update submodules if required.

```
cd quantaco_backend 
git pull origin master

cd quantaco_ui
git pull origin master
```

3. Install docker & docker-compose if required.

https://docs.docker.com/get-docker/
https://docs.docker.com.zh.xy2401.com/v17.12/compose/install/

4. Move to main directory - quantaco

5. Run ``docker-compose up -d``. Make sure you have 3000,8000 ports 
   available on you system. This will spawn 2 docker containers and you can 
   access the application at http://localhost:3000/