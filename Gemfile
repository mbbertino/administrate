source 'https://rubygems.org'

gemspec

gem "administrate-field-image"
gem "autoprefixer-rails"
gem "faker"
gem "globalid"
gem "pg"
gem "redcarpet"
gem "sentry-raven"
gem "unicorn"

group :development, :test do
  gem "appraisal"
  gem "awesome_print"
  gem "bundler-audit", require: false
  gem "byebug"
  gem "dotenv-rails"
  gem "factory_bot_rails"
  gem "i18n-tasks", "0.9.29"
  gem "pry-rails"
end

group :test do
  gem "ammeter"
  gem "capybara", "~> 2.13.0"
  gem "capybara-selenium"
  gem "database_cleaner", require: false
  gem "formulaic"
  gem "launchy"
  gem "pundit"
  gem "selenium-webdriver"
  gem "shoulda-matchers"
  gem "timecop"
  gem "webdrivers"
  gem "webmock"
end

group :staging, :production do
  gem "rack-timeout"
  gem "uglifier"
end
