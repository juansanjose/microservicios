FROM ruby:2.7.1-slim

ENV SERVICE_VERSION="v1"

ENV ENABLE_EXTERNAL_BOOK_SERVICE=true


WORKDIR /code

COPY details.rb .

EXPOSE 9080

CMD ["ruby","details.rb","9080"]




