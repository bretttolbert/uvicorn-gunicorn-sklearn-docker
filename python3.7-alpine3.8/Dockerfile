FROM tiangolo/uvicorn-gunicorn:python3.7-alpine3.8

LABEL maintainer="Brett Tolbert <bretttolbert@gmail.com>"

RUN apk add --update --no-cache g++ gcc gfortran libxslt-dev openblas-dev
RUN pip install Cython numpy scipy