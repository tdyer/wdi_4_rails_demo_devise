source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.0'
# Use postgresql as the database for Active Record
gem 'pg'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.3'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0',          group: :doc

# Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
gem 'spring',        group: :development

gem 'dotenv-rails'
gem 'time_difference'

group :production do
  gem 'rails_12factor'
end

group :development do
  # Add model attributes
  gem 'annotate'

  # help to kill N+1 queries and unused eager loading
  # https://github.com/flyerhzm/bullet. Needs config in development.rb
  gem 'bullet'

  # https://github.com/plentz/lol_dba
  # list columns that should be indexed
  gem 'lol_dba'

  gem 'rails_best_practices', require: false

  # Ruby/CLI: Automatic lossless reduction of all your images
  gem 'smusher'
end

group :test do
  gem 'faker'
  gem 'chronic'
end

group :development, :test do
  gem 'rspec-rails'
  gem 'database_cleaner'
  gem 'shoulda-matchers'
  gem 'guard-rspec', require: false

  gem 'pry-rails'
  gem 'pry-nav'
  gem 'pry-stack_explorer'

  # Turn off verbose logging of asset requests
  gem 'quiet_assets'

  # see Railscast for better_error gem
  # http://railscasts.com/episodes/402-better-errors-railspanel
  # FOR sublime text 3 MUST INSTALL sublime-url-protocol-mac, http://goo.gl/8KX1lb
  # http://goo.gl/8KX1lb
  gem 'better_errors'
  gem 'binding_of_caller'

  # Show a rails panel in Chrome. Requires a Chrome extension.
  # https://github.com/dejan/rails_panel
  gem 'meta_request'
end

gem "devise"