FROM ruby:3.0.5

ENV APP /usr/src/app

WORKDIR $APP

COPY Gemfile $APP/
RUN bundle install
