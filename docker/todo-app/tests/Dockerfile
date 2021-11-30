FROM mjgargani/puppeteer:trybe1.0
WORKDIR /
ADD node_modules.tar.gz .
COPY . .
ENV FRONT_HOST todofrontend
ENV FRONT_PORT 3000
CMD ["npm", "test"]