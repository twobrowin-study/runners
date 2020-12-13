FROM    alpine:latest
RUN     ENVSUBST_RELEASE=v1.2.0 &&\
        apk add curl &&\
        curl -L https://github.com/a8m/envsubst/releases/download/${ENVSUBST_RELEASE}/envsubst-`uname -s`-`uname -m` -o /usr/local/bin/envsubst &&\
        chmod +x /usr/local/bin/envsubst