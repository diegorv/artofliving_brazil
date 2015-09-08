source 'https://rubygems.org'

ruby '2.2.3'

gem 'rails', '4.2.4'
gem 'mysql2'

gem 'sass-rails', '~> 5.0'
gem 'uglifier'  , '>= 1.3.0'
gem 'jquery-rails'

# ------------------------------------------------------------------------------------------------------------------------------

group :production do
  gem 'rails_12factor'
  gem 'rack-timeout'
  gem 'dalli'
  gem 'runtimeerror_notifier'
end

group :development do
  gem 'quiet_assets'
  gem 'rails_best_practices'
  #gem 'bullet'
  #gem 'rack-mini-profiler', require: false
  #gem 'flamegraph'
end

group :development, :test do
  gem 'rspec-rails', '~> 3.0'
  gem 'fuubar'
  #gem 'byebug'
  #gem 'web-console', '~> 2.0'

  gem 'spring'
  gem 'spring-commands-rspec'
end

group :test do
  gem 'shoulda-matchers', require: false

  gem 'database_cleaner'
  gem 'connection_pool'
  gem 'factory_girl_rails'

  gem 'capybara'
  gem 'capybara-webkit'
  gem 'selenium-webdriver'

  gem 'forgery'
  gem 'launchy'
  gem 'cpf_cnpj'

  gem 'codeclimate-test-reporter', require: nil
end
