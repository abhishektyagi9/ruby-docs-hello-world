# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.0'

gem 'rails', '~> 5.2.3'

# Backend tools
gem 'aasm', '~> 5.0.8'
gem 'active_storage_validations', '~> 0.8.9'
gem 'administrate', '>= 0.12'
gem 'administrate-field-active_storage'
gem 'administrate-field-nested_has_many'
gem 'administrate-field-scoped_has_many'
gem 'aws-sdk-s3', require: false
gem 'azure-storage', '~> 0.14.0.preview'
gem 'bootstrap4-kaminari-views' # for adminstrate's pagination
gem 'devise', '~> 4.7.3'
gem 'faker'
gem 'money-rails', '~> 1'
gem 'newrelic_rpm'
gem 'pg', '>= 0.18', '< 2.0'
gem 'phony_rails', '~> 0.14.13'
gem 'puma', '~> 4.3'
gem 'pundit'
gem 'rails-settings-cached', '~> 2.0'
gem 'sidekiq'
gem 'sprockets', '3.7.2'
gem 'twilio-ruby', '~> 5.45.0'

# Frontend tools
gem 'bootstrap', '~> 4.5.0'
gem 'haml'
gem 'jbuilder', '~> 2.10'
gem 'jquery-rails'
gem 'sass-rails', '~> 6'
gem 'select2-rails', '<= 5.0'
gem 'simple_form'
gem 'uglifier', '>= 1.3.0'
gem 'webpacker', '~> 4.0'
gem 'wicked'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false

group :development, :test do
  gem 'dotenv-rails'
  gem 'factory_bot_rails'
  gem 'pry-byebug'
  gem 'pry-rails'
  gem 'rails-erd'
  gem 'rspec-rails', '~> 3.8.2'
  gem 'rspec-sidekiq'
  gem 'rubocop-rails'
end

group :development do
  gem 'annotate'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'bullet'
  gem 'haml-lint', require: false
  gem 'letter_opener'
  gem 'listen', '>= 3.0.5', '< 3.3'
  gem 'web-console', '>= 3.3.0'
end

group :test do
  gem 'capybara'
  gem 'capybara-select2'
  gem 'mini_magick'
  gem 'mock_redis'
  gem 'pundit-matchers'
  gem 'selenium-webdriver'
  gem 'shoulda-matchers'
  gem 'simplecov', require: false
  gem 'timecop'
  gem 'webdrivers'
end
