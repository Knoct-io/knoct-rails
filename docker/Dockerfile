FROM ruby:3.0.2
RUN apt-get update -qq && apt-get install -y nodejs postgresql-client
RUN mkdir /knoct-rails
WORKDIR /knoct-rails
ADD . /knoct-rails
RUN bundle install
