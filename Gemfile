source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.4.1'
gem 'bootsnap', '>= 1.1.0', require: false
gem 'coffee-rails', '~> 4.2'
gem 'jbuilder', '~> 2.5'
gem 'pg'
gem 'puma', '~> 3.11'
gem 'rails', '~> 5.2.0'
gem 'rubocop'
gem 'sass-rails', '~> 5.0'
gem 'taps'
gem 'turbolinks', '~> 5'
gem 'uglifier', '>= 1.3.0'
gem 'will_paginate', '~> 3.1'
gem 'faker', :git => 'https://github.com/stympy/faker.git', :branch => 'master'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'sqlite3'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'web-console', '>= 3.3.0'
end

group :test do
  gem 'capybara', '>= 2.15', '< 4.0'
  gem 'selenium-webdriver'
  gem 'chromedriver-helper'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
