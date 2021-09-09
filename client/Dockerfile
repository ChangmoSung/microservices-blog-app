FROM node:alpine

# create-react-app has a bug that prevents it from running correctly in a docker container.
# ENV CI=true is to fix the issue.
ENV CI=true

WORKDIR /app

COPY package.json ./
RUN npm install
COPY ./ ./

CMD ["npm", "start"]

# docker build -t changmosung/client .
# docker run -it changmosung/client sh