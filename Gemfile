# A sample Gemfile
source "http://rubygems.org"

gem "rails", "3.0.3"

gem 'haml', '3.0.25'

gem 'will_paginate', '3.0.pre2'

gem 'capistrano'
gem 'capistrano-ext'

group :production do
  gem 'mysql2'
end

group :test do
  gem 'sqlite3-ruby', '1.3.2'
  gem 'rspec', '2.0.0', :groups => [:development, :test]
  gem 'rspec-core', '2.0.0', :groups => [:development, :test]
  gem 'rspec-expectations', '2.0.0', :groups => [:development, :test]
  gem 'rspec-mocks', '2.0.0', :groups => [:development, :test]
  gem 'rspec-rails', '2.0.0', :groups => [:development, :test]
  
  gem 'cucumber', '0.9.2', :groups => [:development, :test]
  gem 'cucumber-rails', '0.3.2', :groups => [:development, :test]
  gem 'database_cleaner', '0.5.2', :groups => [:development, :test]
  
  gem 'selenium-client', '1.2.18', :groups => [:development, :test]
  gem 'term-ansicolor', '1.0.5', :groups => [:development, :test]
  gem 'webrat', '0.7.2', :groups => [:development, :test]
end

group :development do
  gem 'sqlite3-ruby', '1.3.2'
end
