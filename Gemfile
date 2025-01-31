# By placing all of Spree's shared dependencies in this file and then loading
# it for each component's Gemfile, we can be sure that we're only testing just
# the one component of Spree.
source 'https://rubygems.org'

gem 'coffee-rails'
gem 'sass-rails'
gem 'sqlite3', platforms: [:ruby, :mingw, :mswin, :x64_mingw]
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw]

group :test do
  gem 'capybara', '~> 2.4'
  gem 'capybara-screenshot', '~> 1.0'
  gem 'database_cleaner', '~> 1.3'
  gem 'email_spec'
  gem 'factory_girl_rails', '~> 4.7'
  gem 'launchy'
  gem 'rspec-activemodel-mocks', '~> 1.0'
  gem 'rspec-collection_matchers'
  gem 'rspec-its'
  gem 'rspec-rails', '~> 3.4'
  gem 'rspec_junit_formatter'
  gem 'simplecov'
  gem 'webmock', '~> 2.1'
  gem 'poltergeist', '~> 1.10'
  gem 'timecop'
  gem 'with_model'
  gem 'mutant-rspec', '~> 0.8'
  gem 'shoulda-matchers', '~> 3.1'
  gem 'shoulda-callback-matchers', '~> 1.1'
  gem 'rails-controller-testing'
end

group :test, :development do
  gem 'rubocop', require: false
  gem 'pry-byebug'
end

gem 'spree', '>= 3.3.0'

gemspec
