source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.4.4'

gem 'rails', '~> 5.2.0'

group :development, :test do
  gem 'sqlite3', '~> 1.3', '>= 1.3.13'
	gem 'rspec-rails', '2.13.1'
end

gem 'railties', '~> 5.2'
gem 'puma', '~> 3.11'
gem 'sass-rails', '~> 5.0', '>= 5.0.7'
gem 'uglifier', '~> 4.1', '>= 4.1.16'
gem 'duktape'
gem 'coffee-rails', '~> 4.2', '>= 4.2.2'
gem 'turbolinks', '~> 5.1', '>= 5.1.1'
gem 'jbuilder', '~> 2.7'
gem 'bootsnap', '>= 1.1.0', require: false

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console', '>= 3.3.0'
end

group :test do
  gem 'capybara', '~> 3.4', '>= 3.4.2'
	gem 'selenium-webdriver', '~> 3.13', '>= 3.13.1'
  gem 'chromedriver-helper'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
gem 'jquery-rails', '~> 4.3', '>= 4.3.3'

group :doc do
	gem 'sdoc', '~> 1.0'
end

group :production do
  gem 'pg', '~> 1.0'
  gem 'rails_12factor', '~> 0.0.3'
end

