source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '6.1.3'
# Use sqlite3 as the database for Active Record
#gem 'sqlite3'
# Use Puma as the app server
#gem 'therubyracer',  platforms: :ruby
gem 'puma', '5.2.2'
# Use SCSS for stylesheets
gem 'sass-rails', '6.0.0'
gem 'webpacker' , '5.2.1'
# Use Uglifier as compressor for JavaScript assets
#gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'mini_racer', platforms: :ruby

# Use CoffeeScript for .coffee assets and views
#gem 'coffee-rails', '~> 4.2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '5.2.1'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '2.10.0'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use ActiveStorage variant
# gem 'mini_magick', '~> 4.8'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '1.7.2', require: false

group :development, :test do
  gem 'sqlite3' , '1.4.2'
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', '11.1.3' , platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '4.1.0'
  gem 'rack-mini-profiler' , '2.3.1'
  gem 'listen', '3.4.1'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring','2.1.1'
  #gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '3.35.3'
  gem 'selenium-webdriver' , '3.142.7'
  # Easy installation and use of chromedriver to run system tests with Chrome
  #gem 'chromedriver-helper'
  gem 'webdrivers', '4.6.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
#gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
