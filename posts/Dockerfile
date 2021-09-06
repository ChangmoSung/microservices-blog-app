FROM node:alpine

WORKDIR /app

COPY package.json ./
RUN npm install
COPY ./ ./

CMD ["npm", "start"]

# docker build -t changmosung/posts .
# docker run -it changmosung/posts sh