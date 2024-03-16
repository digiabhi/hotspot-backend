FROM node

WORKDIR /developer/nodejs/hotspotbackend

COPY .. .

RUN npm ci

CMD ["npm", "run", "dev"]