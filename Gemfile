source 'https://rubygems.org'
source 'http://gems.github.com'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.0'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

gem "devise"

# mongoid 4
gem "mongoid", github: "mongoid/mongoid"
gem "mongoid_paranoia"
gem "symbolize"
gem "mongoid-versioning"
# Mongo on Heroku
gem "bson"
gem "moped", github: "mongoid/moped"

gem 'bson_ext'

gem 'haml-rails'
gem 'erb2haml'

gem 'backbone-on-rails'

gem 'therubyracer' # javascript runtime。lessをコンパイルするために必要
gem 'less-rails' # Railsでlessを使えるようにする。Bootstrapがlessで書かれているため
gem 'twitter-bootstrap-rails'
gem 'font-awesome-rails'
gem 'bootstrap-sass', '2.3.2.0'

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

gem 'rserve-client', require: 'rserve'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development
gem "heroku-api", "0.3.18" #追記
gem 'cowsay'

group :development do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'

  gem "capistrano", '~> 3.1'
  gem 'capistrano-rails'
  gem 'capistrano-bundler'
  gem 'capistrano-rbenv', '~> 2.0'
  gem "capistrano3-unicorn"

  gem "pry-rails"
  # gem "pry-exception_explorer"
  # gem "pry-nav"
end

group :test do
  gem "rspec-rails", '~> 3.0.0'
  gem "spork-rails"
  gem 'webmock'
end
