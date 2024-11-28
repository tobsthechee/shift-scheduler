FROM node:18
WORKDIR /usr/src/app/frontend
COPY package*.json ./
RUN npm cache clean --force
RUN npm install -g npm@10.9.1
COPY . .
EXPOSE 3000
CMD ["npm", "run", "build"]
