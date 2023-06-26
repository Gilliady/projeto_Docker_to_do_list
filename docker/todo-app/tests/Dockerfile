FROM betrybe/puppetter:1.0 as todotests
WORKDIR /app/tests
ADD ./node_modules.tar.gz ./
COPY ./ /app/tests/
ENTRYPOINT [ "npm" ]
CMD [ "test" ]