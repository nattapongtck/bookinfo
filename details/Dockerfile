FROM ruby:2.7.1

WORKDIR /usr/src/app

COPY src/ /usr/src/app

RUN bundle install

EXPOSE 9080

CMD ["ruby","details.rb","9080"]
