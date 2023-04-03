FROM mcr.microsoft.com/vscode/devcontainers/typescript-node:0-14

RUN apt-get update 
RUN npm install -g powerbi-visuals-tools@latest
RUN npm install powerbi-visuals-api --save-dev
RUN pbiviz --install-cert


COPY . .


EXPOSE 8080

