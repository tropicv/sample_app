source 'https://rubygems.org'
ruby '2.4.4'
#ruby-gemset=railstutorial_rails_5_2_0

gem 'rails', '~> 5.2.0'

group :development, :test do
  gem 'sqlite3', '~> 1.3', '>= 1.3.13'
	gem 'rspec-rails', '2.13.1'
end

group :test do
	gem 'selenium-webdriver', '~> 3.13', '>= 3.13.1'
  gem 'capybara', '~> 3.4', '>= 3.4.2'
end

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false

gem 'sass-rails', '~> 5.0', '>= 5.0.7'
gem 'uglifier', '~> 4.1', '>= 4.1.16'
gem 'coffee-rails', '~> 4.2', '>= 4.2.2'
gem 'jquery-rails', '~> 4.3', '>= 4.3.3'
gem 'turbolinks', '~> 5.1', '>= 5.1.1'
gem 'jbuilder', '~> 2.7'

group :doc do
	gem 'sdoc', '~> 1.0'
end

group :production do
  gem 'pg', '~> 1.0'
  gem 'rails_12factor', '~> 0.0.3'
end

