FROM node:14-alpine
WORKDIR /
EXPOSE 3000
ADD node_modules.tar.gz .
COPY . .
ENV REACT_APP_API_HOST todobackend
ENV REACT_APP_API_PORT 3001
CMD ["npm", "start"]