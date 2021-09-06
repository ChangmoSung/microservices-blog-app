FROM node:alpine

WORKDIR /app

COPY package.json ./
RUN npm install
COPY ./ ./

CMD ["npm", "start"]

# docker build -t changmosung/event-bus .
# docker run -it changmosung/event-bus sh