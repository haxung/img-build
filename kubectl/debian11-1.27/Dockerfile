FROM debian:bullseye-slim


RUN apt-get update && apt-get install -y curl sed
RUN curl -LO https://storage.googleapis.com/kubernetes-release/release/1.27.4/bin/linux/amd64/kubectl && chmod +x ./kubectl && mv ./kubectl /usr/local/bin/kubectl
