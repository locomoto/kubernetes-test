FROM nginx:alpine

RUN apk add --update \
    python \
    python-dev \
    py-pip \
    && rm -rf /var/cache/apk/*

RUN pip install acme-nginx


