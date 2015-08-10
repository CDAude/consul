source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.3'
# Use PostgreSQL
gem 'pg'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc
gem 'devise'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'
gem 'acts_as_commentable_with_threading'
gem 'acts-as-taggable-on'
gem "responders"
gem 'foundation-rails'
gem 'acts_as_votable'
gem "recaptcha", require: "recaptcha/rails"
gem 'ckeditor'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'rspec-rails', '~> 3.0'
  gem 'capybara'
  gem 'factory_girl_rails'
  gem 'launchy'
  gem 'quiet_assets'
  gem 'letter_opener_web', '~> 1.2.0'
  gem 'i18n-tasks'
  gem 'capistrano', '3.4.0',           require: false
  gem "capistrano-bundler", '1.1.4',   require: false
  gem "capistrano-rails", '1.1.3',     require: false
  gem "capistrano-rvm",                require: false
  gem "capistrano-passenger",          require: false
end

group :test do
  gem 'database_cleaner'
  gem 'poltergeist'
  gem 'coveralls', require: false
end

group :test do
  gem 'email_spec'
end
