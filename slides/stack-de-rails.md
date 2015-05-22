##  Stack de rails

*Dockerfile*
```
FROM ruby:2.1.5
RUN apt-get update -qq && apt-get install -y build-essential libpq-dev
WORKDIR /myapp
ADD Gemfile /myapp/Gemfile
RUN bundle install
ADD . /myapp
```

*Gemfile*
```
source 'https://rubygems.org'
gem 'rails', '4.2.0'
```
