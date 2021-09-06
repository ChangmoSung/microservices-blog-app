FROM node:alpine

WORKDIR /app

COPY package.json ./
RUN npm install
COPY ./ ./

CMD ["npm", "start"]

# docker build -t changmosung/query .
# docker run -it changmosung/query sh