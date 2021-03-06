source "https://rubygems.org"

ruby "2.1.6"

# Ruby on Rails
gem "rails", "4.2.1"
# A gem to automate using jQuery with Rails
gem "jquery-rails"
# Pg is the Ruby interface to the PostgreSQL RDBMS
gem "pg"
# Ruby on Rails stylesheet engine for Sass
gem "sass-rails"
# Slim templates generator for Rails 3 and 4
gem "slim-rails"
# Ruby wrapper for UglifyJS JavaScript compressor.
gem "uglifier"
# Unicorn: Rack HTTP server for fast clients and Unix
# gem "unicorn"

group :development do
  # A Ruby static code analyzer, based on the community Ruby style guide.
  gem "rubocop", require: false
end

group :development, :test do
  # Byebug is a simple to use, feature rich debugger for Ruby 2.
  gem "byebug"
  # "Did you mean?" experience in Ruby
  gem "did_you_mean"
  # Loads environment variables from `.env`.
  gem "dotenv-rails"
  # A library for generating fake data
  gem "faker"
  # Manage Procfile-based applications
  gem "foreman"
  # Hirb provides a mini view framework for console applications and uses
  # it to improve ripl(irb)'s default inspect output.
  gem "hirb"
  # Manage translation and localization with static analysis, for Ruby i18n
  gem "i18n-tasks", require: false
  # An IRB alternative and runtime developer console
  gem "pry-rails"
  # Behaviour Driven Development for Ruby
  gem "rspec-rails", "~> 3.0"
end

group :test do
  # Acceptance test framework for web applications
  gem "capybara"
  # Database Cleaner is a set of strategies for cleaning your database in Ruby.
  gem "database_cleaner"
  # A library for setting up Ruby objects as test data.
  gem "factory_girl_rails"
  # Phantomjs via Rubygems
  gem "phantomjs", require: "phantomjs/poltergeist"
  # A PhantomJS driver for Capybara
  gem "poltergeist"
  # Collection of testing matchers
  gem "shoulda-matchers"
  # SimpleCov is a code coverage analysis tool for Ruby
  gem "simplecov", require: false
end
