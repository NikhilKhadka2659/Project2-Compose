FROM jenkins/jenkins:lts-jdk11

USER root

# Install Docker CLI + Node.js + npm
RUN apt-get update && \
    apt-get install -y docker.io nodejs npm && \
    rm -rf /var/lib/apt/lists/*

USER jenkins
