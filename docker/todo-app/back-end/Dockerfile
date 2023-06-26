FROM node:16-alpine3.12 as todobackend
EXPOSE 3001
WORKDIR /app/back-end
ADD ./node_modules.tar.gz ./
COPY ./ /app/back-end
ENTRYPOINT [ "npm" ]
CMD [ "start" ]