source 'https://rubygems.org'
ruby "1.9.3"

gem 'rails', '3.2.11'
gem 'bootstrap-sass', '2.1'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'pg'

gem 'activeadmin'
gem 'omniauth-twitter'
#gem 'omniauth-facebook'

gem 'paperclip'
gem 'aws-sdk'
gem 'cocoon'

gem 'friendly_id'


#gem 'haml-rails'
 
group :production do
 gem 'thin'
 gem 'newrelic_rpm'
 gem 'rails_12factor'
end

group :development, :test do
  gem 'sqlite3'
  gem 'annotate'
  gem 'thin'
  gem 'rack-mini-profiler'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

# Jquery Gem removed  Jquery UI in 3.0 breaking active admin...
gem "jquery-rails", "2.3.0"

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug'
