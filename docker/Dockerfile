FROM node:18-alpine

LABEL "Project"="node"

LABEL "Author"="Abdul Shukor"

ENV NODE_ENV=production

WORKDIR /app

COPY ["package.json", "package-lock.json*", "./"]

RUN npm install --production

COPY . .

CMD [ "node", "server.js" ]
