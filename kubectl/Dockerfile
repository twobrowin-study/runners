FROM    alpine:latest
RUN     apk add curl && \
        KUBECTL_RELEASE=$(curl -s https://storage.googleapis.com/kubernetes-release/release/stable.txt) && \
        curl -L -o /usr/bin/kubectl "https://storage.googleapis.com/kubernetes-release/release/${KUBECTL_RELEASE}/bin/linux/amd64/kubectl" && \
        chmod +x /usr/bin/kubectl