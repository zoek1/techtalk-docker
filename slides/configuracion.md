##  Configuración

*config/database.yml*
```ruby
default: &default
  adapter: postgresql
  encoding: unicode
  datasabe: postgres
  pool: 5
  username: postgres
  password:
  host: db
```

*Gemfile*
```ruby
gem 'therubyracer', platforms: :ruby
```
