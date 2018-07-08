FROM node:8
LABEL maintainer "himstone.yang@gmail.com"
COPY . .
RUN npm install
RUN npm run build
EXPOSE 3000
CMD ["npm", "start"]

