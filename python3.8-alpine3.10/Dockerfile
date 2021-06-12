FROM tiangolo/uvicorn-gunicorn:python3.8-alpine3.10

MAINTAINER "Brett Tolbert <bretttolbert@gmail.com>"

RUN apk add --update --no-cache g++ gcc gfortran libxslt-dev openblas-dev
RUN pip install starlette coverage snowballstemmer
RUN pip install cython numpy scipy lxml>=4.6.3
RUN pip install scikit-learn>=0.24.2
