FROM ruby:3.2

RUN gem install bundler

WORKDIR /usr/src/app

COPY Gemfile* ./
RUN bundle install

EXPOSE 4000