FROM node:argon

ADD . /app

RUN cd /app; npm install --production

EXPOSE 8123

CMD ["node", "/app/index.js"]