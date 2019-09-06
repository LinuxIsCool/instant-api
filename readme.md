
# Instant API
    git clone git@github.com:LinuxIsCool/instant-api.git 
    cd instant-api
    docker build -t myimage .
    docker run -d --name mycontainer -p 80:80 myimage

Navigate to localhost/hello or localhost/docs  

References:  
https://github.com/tiangolo/uvicorn-gunicorn-fastapi-docker  
https://www.uvicorn.org/  
https://fastapi.tiangolo.com/  

