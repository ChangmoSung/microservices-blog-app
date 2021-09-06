FROM node:alpine

WORKDIR /app

COPY package.json ./
RUN npm install
COPY ./ ./

CMD ["npm", "start"]

# docker build -t changmosung/moderation .
# docker run -it changmosung/moderation sh