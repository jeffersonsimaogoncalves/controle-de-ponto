source 'https://rubygems.org'

gem 'rails', '4.2.0'

gem 'jquery-rails'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'

gem 'devise'
gem 'simple_form'

gem 'bootstrap-sass', '~> 3.2.0'
gem 'font-awesome-rails'

gem 'time_diff'
gem 'mongoid', '~> 4.0.0'
gem 'enumerize'

group :production do
  gem 'unicorn'
end

group :development, :test do
  gem 'rspec-rails'
  gem 'rubocop', require: false
  gem 'mailcatcher'
  gem 'byebug'
  gem 'zeus'
  gem 'database_cleaner'
  gem 'factory_girl_rails'
end

group :test do
  gem 'shoulda-matchers'
  gem 'mongoid-rspec', '~> 2.1.0'
  gem 'codeclimate-test-reporter'
  gem 'simplecov', require: false
  gem 'turnip'
  gem 'rspec_candy'
end