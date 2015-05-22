##  Hello World! - Files

*Gemfile*
```ruby
source 'https://rubygems.org'
gem 'sinatra'
```

*Dockerfile*
```
FROM ruby:2.1.5
ADD . /app
WORKDIR  /app
RUN bundle install
# ENTRYPOINT ruby app.rb
```

*app.rb*
```ruby
require 'sinatra'

get '/' do
  "Hola mundo desde mi contenedor!"
end
```
