source 'https://rubygems.org'

gem 'rails', '4.2.6'
gem 'pg', '~> 0.15'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'sdoc', '~> 0.4.0', group: :doc
gem 'bcrypt', '~> 3.1.7'
gem 'figaro'
gem 'rails_12factor'
gem 'httparty'
gem 'enumerize'
gem 'grape'
gem 'rack-cors', :require => 'rack/cors'
gem 'grape-active_model_serializers'
gem 'grape-swagger', github: 'LeFnord/grape-swagger', ref: 'f82887f'
gem 'grape-swagger-rails'
gem 'haml'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
  gem 'rspec-rails', '~> 3.4'
  gem 'spring-commands-rspec'
  gem 'vcr'
  gem 'webmock'
  gem 'rspec-activemodel-mocks'
  gem 'database_cleaner'
  gem 'factory_girl_rails'
end

group :test do
  gem 'shoulda-matchers', '~> 3.1', require: false
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'guard-rspec', require: false
  gem 'web-console', '~> 2.0'
end