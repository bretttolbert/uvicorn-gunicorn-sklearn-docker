FROM tiangolo/uvicorn-gunicorn:python3.7-alpine3.8

LABEL maintainer="Brett Tolbert <bretttolbert@gmail.com>"

RUN apk add --update --no-cache g++ gcc gfortran libxslt-dev openblas-dev
RUN pip install starlette coverage snowballstemmer
RUN pip install cython numpy scipy lxml>=4.1.1
RUN pip install scikit-learn>=0.20.3
