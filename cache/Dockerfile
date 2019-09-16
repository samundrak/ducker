FROM node
LABEL maintainer="samundrak@yahoo.com"
RUN git clone -q https://github.com/docker-in-practice/todo.git
WORKDIR todo
ARG CACHEBUST=no
RUN npm install
EXPOSE 8000
CMD [ "npm" ,"start"]