source 'https://rubygems.org'

ruby '1.9.3'
#ruby-gemset=railstutorial_rails_4_0

gem 'rails', '4.0.2'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

group :development, :test do
	gem 'sqlite3', '1.3.8'
	gem 'rspec-rails', '2.13.1'
	gem 'spork-rails', '4.0.0'
	gem 'guard-spork', '1.5.0'
	gem 'childprocess', '0.3.6'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '4.0.1'
  gem 'coffee-rails', '4.0.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '2.1.1'
end

gem 'jquery-rails', '3.0.4'

group :test do
  gem 'selenium-webdriver', '2.35.1'
  gem 'capybara', '2.1.0'
  
  # Uncomment this line on OS X.
  gem 'growl', '1.0.3'

  # Uncomment these lines on Linux.
  # gem 'libnotify', '0.8.0'

  # Uncomment these lines on Windows.
  # gem 'rb-notifu', '0.0.4'
  # gem 'win32console', '1.3.2'
  # gem 'wdm', '0.1.0'
end

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'
gem 'turbolinks', '1.1.1'

# To use Jbuilder templates for JSON
gem 'jbuilder', '1.0.2'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'

group :doc do
	gem 'sdoc', '0.3.20', require: false
end

group :production do
	gem 'rails_12factor', '0.0.2'
	gem 'pg', '0.15.1'
end
