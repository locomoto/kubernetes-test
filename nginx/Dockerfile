FROM nginx:alpine

RUN apk add --update \
    musl-dev \
    libffi-dev \
    linux-headers \
    openssl-dev \
    gcc \
    python \
    python-dev \
    py-pip \
    && rm -rf /var/cache/apk/*

RUN pip install acme-nginx


