FROM node:14

WORKDIR /app
COPY package.json package-lock.json /app/
RUN npm install

COPY index.js /app/

CMD ["node", "index.js"]
