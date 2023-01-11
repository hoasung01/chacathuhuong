source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.6'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails', branch: 'main'
gem 'rails', '~> 6.1.7'
# Use sqlite3 as the database for Active Record
gem 'sqlite3', '~> 1.4'
# Use Puma as the app server
gem 'puma', '~> 5.0'
# Use SCSS for stylesheets
gem 'sass-rails', '>= 6'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.7'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.4', require: false

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 4.1.0'
  # Display performance information such as SQL time and flame graphs for each request in your browser.
  # Can be configured to work on production as well see: https://github.com/MiniProfiler/rack-mini-profiler/blob/master/README.md
  gem 'rack-mini-profiler', '~> 2.0'
  gem 'listen', '~> 3.3'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 3.26'
  gem 'selenium-webdriver', '>= 4.0.0.rc1'
  # Easy installation and use of web drivers to run system tests with browsers
  gem 'webdrivers'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]


gem "solidus_core", "~> 3.2"
gem "solidus_backend", "~> 3.2"
gem "solidus_api", "~> 3.2"
gem "solidus_sample", "~> 3.2"
gem 'canonical-rails'
gem 'solidus_support'
gem 'truncate_html'
gem 'view_component', '~> 2.46'

group :development, :test do
  gem 'rspec-rails'
  gem 'apparition', '~> 0.6.0', github: 'twalpole/apparition'
  gem 'rails-controller-testing', '~> 1.0.5'
  gem 'rspec-activemodel-mocks', '~> 1.1.0'
  gem 'capybara-screenshot', '~> 1.0'
  gem 'database_cleaner', '~> 1.7'
  gem 'factory_bot', '>= 4.8'
  gem 'factory_bot_rails'
  gem 'ffaker', '~> 2.13'
  gem 'rubocop', '~> 1.0'
  gem 'rubocop-performance', '~> 1.5'
  gem 'rubocop-rails', '~> 2.3'
  gem 'rubocop-rspec', '~> 2.0'
end

# FIXME: Please remove this line if `solidus_auth_devise` appears anywhere else in the gemfile
#        or replace it with a simple `gem 'solidus_auth_devise'` otherwise.
gem 'solidus_auth_devise' unless File.read(__FILE__).lines[__LINE__..-1].grep(/solidus_auth_devise/).any?

