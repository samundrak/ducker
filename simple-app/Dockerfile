FROM node:10
RUN git clone https://github.com/samundrak/virtual-keyboard.git
WORKDIR virtual-keyboard   
run npm i -g yarn
RUN yarn && yarn build
RUN npm i -g serve 
CMD [ "serve","build" ]