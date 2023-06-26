FROM node:16-alpine3.12 as todofrontend
EXPOSE 3000
WORKDIR /app/front-end
ADD /node_modules.tar.gz ./
COPY ./ /app/front-end/
ENTRYPOINT [ "npm" ]
CMD [ "start" ]