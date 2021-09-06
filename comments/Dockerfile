FROM node:alpine

WORKDIR /app

COPY package.json ./
RUN npm install
COPY ./ ./

CMD ["npm", "start"]

# docker build -t changmosung/comments .
# docker run -it changmosung/comments sh