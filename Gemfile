source 'https://rubygems.org'

gem 'rails', '4.1.1'
gem 'sass-rails', '~> 4.0.3'
gem 'uglifier', '~> 2.5.0'
gem 'coffee-rails', '~> 4.0.1'
gem 'jquery-rails', '~> 3.1.0'
gem 'turbolinks', '~> 2.2.2'
gem 'omniauth', '~> 1.2.1'
gem 'omniauth-twitter', '~> 1.0.1'
gem 'kaminari', '~> 0.15.1'
gem 'kaminari-bootstrap', '~> 3.0.1'
gem "ransack", '~> 1.2.2'
gem 'carrierwave', '~> 0.10.0'
gem 'mini_magick', '~> 3.7.0'
gem 'newrelic_rpm'

group :development do
  gem "capistrano", "3.1.0"
  gem "capistrano-rails"
  gem "capistrano-bundler"
  gem "capistrano3-unicorn"
  gem 'spring'
end

group :development, :test do
  gem 'rspec'
  gem 'factory_girl_rails', '~> 4.4.1'
end

group :test do
  gem 'shoulda-matchers', '~> 2.6.0'
  gem 'capybara', '~> 2.2.1'
  gem 'poltergeist', '~> 1.5.0'
  gem 'database_cleaner', '~> 1.2.0'
end

group :development, :test, :staging do
  gem 'sqlite3', '~> 1.3.9'
end

group :staging, :production do
  gem 'unicorn'
end

group :production do
  gem 'pg'
end
