FROM debian:bullseye-slim

RUN sed -i 's/deb.debian.org/mirrors.ustc.edu.cn/g' /etc/apt/sources.list
RUN apt-get update && apt-get install -y curl apt-transport-https ca-certificates
RUN curl -Lo /usr/local/bin/kubectl https://storage.googleapis.com/kubernetes-release/release/v1.27.4/bin/linux/amd64/kubectl
RUN chmod +x /usr/local/bin/kubectl
