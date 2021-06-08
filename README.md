# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

## Initial SetUp gem setup
```ruby
  gem 'sqlite3','~> 1.3.0'
  gem 'mongoid'
```

## connect mongodb and active record
```ruby
  rails g mongoid:config
  #creates mongoid.yml file, parameters taken automatically if you installed the mongodb and running like port nnumber db name.
```
## Run the server 
* rails s
