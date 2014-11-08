source 'https://rubygems.org'
# ruby '2.0.0'

gem 'rails', '~> 4.1.4'
gem 'foundation-rails'
gem 'sprockets', '2.11.3'
gem 'bcrypt', '~> 3.1.2'
gem 'faker', '1.1.2'
gem 'will_paginate'
gem 'tzinfo-data'
gem 'best_in_place', github: 'aaronchi/best_in_place'
gem 'figaro'
gem 'pg'

# Use unicorn as the app server
gem 'unicorn'

# Deploy with Capistrano
gem 'capistrano', '~> 3.1'

group :development, :test do
  # gem 'sqlite3', '1.3.8'
  gem 'rspec-rails', '~> 2.14.0'
  gem 'capistrano-rails'
  gem 'capistrano-bundler'
  gem 'capistrano-rbenv', '~> 2.0', require: false
  # The following optional lines are part of the advanced setup.
  # gem 'guard-rspec', '2.5.0'
  # gem 'spork-rails', '4.0.0'
  # gem 'guard-spork', '1.5.0'
end

group :test do
  gem 'selenium-webdriver', '2.35.1'
  gem 'capybara', '2.1.0'
  gem 'factory_girl_rails', '4.2.0'
  # gem 'cucumber-rails', '1.4.0', :require => false
  # gem 'database_cleaner', github: 'bmabey/database_cleaner'

  # Uncomment this line on OS X.
  # gem 'growl', '1.0.3'

  # Uncomment these lines on Linux.
  # gem 'libnotify', '0.8.0'

  # Uncomment these lines on Windows.
  # gem 'rb-notifu', '0.0.4'
  # gem 'wdm', '0.1.0'
end

gem 'sass-rails', '~> 4.0.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'roo'
gem 'uglifier', '>= 1.3.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

group :production do
  gem 'rails_12factor', '0.0.2'
end

