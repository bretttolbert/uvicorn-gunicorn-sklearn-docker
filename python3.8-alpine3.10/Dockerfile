FROM tiangolo/uvicorn-gunicorn:python3.8-alpine3.10

MAINTAINER "Brett Tolbert <bretttolbert@gmail.com>"

RUN pip install --upgrade pip
RUN apk add --update --no-cache g++ gcc gfortran libxslt-dev openblas-dev
RUN pip install starlette coverage snowballstemmer
RUN pip install lxml>=4.6.3
RUN pip install cython>=0.29.23
RUN pip install numpy>=1.20.3
RUN pip install scipy>=1.6.3
RUN pip install scikit-learn>=0.24.2
