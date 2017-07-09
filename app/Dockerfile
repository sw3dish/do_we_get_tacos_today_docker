FROM ruby:2.4.1
LABEL maintainer="sw3dish (Colin Burr)"

ADD Gemfile .

VOLUME /srv/www
WORKDIR /srv/www

RUN bundle install

EXPOSE 8000
