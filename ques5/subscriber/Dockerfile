FROM node:alpine
WORKDIR /usr/ca/subscriber
COPY subscriber.js /usr//subscriber
RUN npm install mqtt
CMD ["node", "subscriber.js"]


