source 'https://rubygems.org'

gem 'base_indexer', '~> 4'
gem 'revs-utils', '>= 2.2.0'
gem 'discovery-indexer', '~>3', '>= 3.0.1'
gem 'dor-fetcher', '>= 1.1.1'
gem 'mysql2'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '>= 5.2.2.1'
gem 'responders', '~> 2.0'
gem 'coffee-script'
gem 'sass-rails'
gem 'rack', '>= 2.0.6'

# Use sqlite3 as the database for Active Record
gem 'sqlite3'
# Use SCSS for stylesheets

gem 'config'
gem 'honeybadger', '~> 3.1'
gem 'okcomputer' # for monitoring

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
gem 'therubyracer',  platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0',          group: :doc

# Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
gem 'spring',        group: :development

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]

# testing
group :test do
	gem 'rspec-rails'
	gem 'simplecov', :require => false
	gem 'simplecov-rcov', :require => false
  gem 'equivalent-xml'
end

# gems necessary for capistrano deployment
group :deployment do
  gem 'capistrano', '~> 3.0'
  gem 'capistrano-bundler'
  gem 'capistrano-rails'
	gem 'capistrano-passenger'
	gem 'capistrano-shared_configs'
  gem 'dlss-capistrano'
  gem 'capistrano-rvm'
end

gem 'coveralls', require: false
