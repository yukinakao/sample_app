source 'https://rubygems.org'
ruby '2.1.5'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.0'

gem 'sass'
gem 'bootstrap-sass'
gem 'sprockets'
gem 'twitter-bootstrap-rails'
gem 'twitter-bootstrap3-rails'
gem 'autoprefixer-rails'



# Use sqlite3 as the database for Active Record
# gem 'sqlite3'
# gem 'sqlite3', groups: %w(test development),require :false
# gem 'pg', groups: %w(production),require: false

group :development, :test, :production do
	#gem 'sqlite3'
	gem 'pg'
end

# Use SCSS for stylesheets
gem 'sass-rails'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier'

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder'

# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', group: :doc

group :doc do
	#gem 'sdoc', require: false
end

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console'
  
  # Add script for SAMPLE_APP
  gem 'rspec-rails'
  gem 'guard'
  gem 'guard-rspec'
  gem 'spork-rails'
  gem 'guard-spork'
  gem 'childprocess'
  
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]



#Added script by myself from this comment

group :production do
	#gem 'pg'
	gem 'rails_12factor'
end

# Add script for 'rails generate scaffold'
gem 'execjs'

if RUBY_PLATFORM =~ /mingw/
  gem 'therubyracer', :path => '../../Ruby21-x64/lib/ruby/gems/2.1.0/gems/therubyracer-0.11.0beta1-x86-mingw32'
else
  gem 'libv8'
  gem 'therubyracer'
end

gem 'rb-readline'

group :test do
	gem 'selenium-webdriver'
	gem 'capybara'
end


