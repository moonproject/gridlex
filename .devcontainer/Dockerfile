FROM node:20.10.0

RUN apt-get update -y && apt-get install -y git python3-pip jq vim && rm -rf /var/lib/apt/lists/*

RUN pip3 install detect-secrets --break-system-packages
