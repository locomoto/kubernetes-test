FROM nginx:alpine

RUN apk add --update \
    musl-dev \
    libffi-dev \
    libssl-dev \
    gcc \
    python \
    python-dev \
    python-pip \
    py-pip \
    && rm -rf /var/cache/apk/*

RUN pip install acme-nginx


