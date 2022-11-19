FROM node
WORKDIR ./client
ENV NODE_ENV=development
COPY . .
RUN npm install
EXPOSE 3000
CMD npm run start