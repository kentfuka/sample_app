source 'https://rubygems.org'

gem 'rails', '3.2.2'
gem 'sqlite3','1.3.5'

group :production, :staging do
end

group :development do
  gem 'rspec-rails', '2.6.1'
end

group :test do
  gem 'rspec-rails', '2.6.1'
  gem 'webrat','0.7.1'
  gem 'spork','0.9.0.rc8'
end

# Original attempt to configure for Heroku, but we don't have Postgres installed on the laptop, so the "pg" gem
# Installation fails.
#
# gem 'rails', '3.2.2'
# 
# group :production, :staging do
#   gem "pg"
# end
# 
# group :development do
#   gem 'sqlite3','1.3.5'
#   gem 'rspec-rails', '2.6.1'
# end
# 
# group :test do
#   gem 'rails', '3.2.2'
#   gem 'sqlite3','1.3.5'
#   gem 'rspec-rails', '2.6.1'
#   gem 'webrat','0.7.1'
#   gem 'spork','0.9.0.rc8'
# end

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer'

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'
