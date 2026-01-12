FROM node:20

RUN npm install -g @devvit/cli prettier eslint && \
    ln -s $(npm root -g)/@devvit/cli/bin/devvit.js /usr/local/bin/devvit

WORKDIR /workspace

