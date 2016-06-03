FROM ruby:2.3

RUN mkdir -p /app
WORKDIR /app

RUN apt-get update -qq && apt-get install -y build-essential
RUN gem install slanger

EXPOSE 4567

