 # Dockerfile for React
FROM node:14

WORKDIR /CodeEase

COPY package.json /CodeEase/
COPY yarn.lock /CodeEase/
RUN yarn install

COPY . /CodeEase/

EXPOSE 3000

CMD ["yarn", "start"]