

Quick-start: pull the latest image I've published to docker.io:

```
docker pull bretttolbert/uvicorn-gunicorn-sklearn-docker:latest
```

How to run the container and open an interactive shell:
```
docker run -it bretttolbert/uvicorn-gunicorn-sklearn:python3.8-alpine3.10 /bin/sh
```

How to run the container and open an interactive shell from Git Bash (MINGW64), assuming you've already configured 'docker' as an alias for 'winpty docker.exe' (note the double slashes):
```
docker run -it bretttolbert/uvicorn-gunicorn-sklearn:python3.8-alpine3.10 //bin//sh
```

For developers/me: Instructions for building from source:

```
git clone https://github.com/bretttolbert/uvicorn-gunicorn-sklearn-docker
cd uvicorn-gunicorn-sklearn-docker\python3.8-alpine3.10
docker build -t bretttolbert/uvicorn-gunicorn-sklearn:python3.8-alpine3.10 .
```

Instructions for pushing built image to docker (basically for me only):
```
docker tag bretttolbert/uvicorn-gunicorn-sklearn:python3.8-alpine3.10 bretttolbert/uvicorn-gunicorn-sklearn:latest
docker push bretttolbert/uvicorn-gunicorn-sklearn:python3.8-alpine3.10
docker push bretttolbert/uvicorn-gunicorn-sklearn:latest
```

