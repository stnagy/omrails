source 'https://rubygems.org'

#ruby 1.9.3 = latest
ruby '1.9.3'

#commented out static version of gems

#gem 'rails', '3.2.12'
gem 'rails', '4.0.0'
gem 'jquery-rails'
gem 'devise'
#gem 'activemodel'
gem 'simple_form', '3.0.0.rc'
gem 'paperclip', github: 'thoughtbot/paperclip', branch: 'rails-4'

#Heroku: Include "rails_12factor" gem to enable all platform features
gem 'rails_12factor'

#gems to help with transition
gem 'protected_attributes'
gem 'rails-observers'
gem 'actionpack-page_caching'
gem 'actionpack-action_caching'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

# Can't use SQLite on Heroku, which is why we can only use it during development. 
# Heroku only uses pg.

group :production do
  gem 'pg'
end

group :development, :test do
  gem 'sqlite3'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  #gem 'sass-rails',   '~> 3.2.3'
  #gem 'coffee-rails', '~> 3.2.1'
  #gem 'bootstrap-sass', '~> 2.2.2.0'
  gem 'sass-rails'
  gem 'coffee-rails'
  gem 'bootstrap-sass'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  #gem 'uglifier', '>= 1.0.3'
  gem 'uglifier'
end



# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'
