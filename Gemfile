source 'https://rubygems.org'

gem 'rails', '4.0.0.rc1'
gem 'jquery-rails'
gem 'pg'
gem 'devise'
gem 'pg_search'
gem 'backbone-on-rails'
gem 'kaminari'

# in production environments by default.
group :assets do
  gem 'sass-rails'
  gem 'coffee-rails'
  gem 'railties'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

group :development do
  gem 'rb-fsevent', '~> 0.9.1'
  gem 'annotate', '~> 2.5.0'
  gem 'pry-rails'
  gem 'powder'
  gem 'mailcatcher'
  gem 'quiet_assets'

  # Guard setup
  gem 'guard'
  gem 'guard-annotate'
  gem 'guard-bundler'
  gem 'guard-spork'
  gem 'guard-rspec'
  gem 'guard-pow'
end

group :test, :development do
  gem 'rspec-rails', '~> 2.11'
  gem 'capybara', '1.1.1'
  gem 'database_cleaner'
end

group :test do
  gem 'spork', '0.9.0.rc9'
  gem 'factory_girl_rails', '1.6.0'
  gem 'shoulda-matchers'
end
