source 'https://rubygems.org'

ruby '2.3.1'

gem 'pg', '~> 0.15'
gem 'puma'
gem 'rails', '4.2.6'

gem 'dotenv-rails', groups: [:development, :test]

gem 'dalli'
gem 'date_validator'
gem 'devise'
gem 'devise-i18n'
gem 'font-awesome-sass'
gem 'haml-rails'
gem 'jquery-rails'
gem 'omniauth-twitter'
gem 'pundit'
gem 'rack-contrib'
gem 'rails-i18n'
gem 'rails_admin'
gem 'rails_admin-i18n'
gem 'rails_locale_detection'
gem 'sass-rails', require: false
gem 'sassc-rails'
gem 'twitter'
gem 'uglifier', '>= 1.3.0'
gem 'virtus'

group :staging, :production do
  gem 'newrelic_rpm'
  gem 'rails_12factor'
  gem 'rapporteur'
end

group :development do
  gem 'derailed'
  gem 'guard-livereload', '~> 2.5', require: false
  gem 'license_finder'
  gem 'pivotal_git_scripts'
  gem 'quiet_assets'
  gem 'web-console', '~> 3.0'
end

group :development, :test do
  gem 'bullet'
  gem 'byebug'
  gem 'parallel_tests'
  gem 'rspec-rails'
  gem 'teaspoon-jasmine'
end

group :test do
  gem 'capybara'
  gem 'capybara-screenshot'
  gem 'chromedriver-helper'
  gem 'codeclimate-test-reporter', require: nil
  gem 'database_cleaner'
  gem 'fuubar'
  gem 'launchy'
  gem 'phantomjs', require: 'phantomjs/poltergeist'
  gem 'poltergeist'
  gem 'rspec_junit_formatter', require: false
  gem 'selenium-webdriver'
  gem 'shoulda-matchers'
  gem 'vcr'
  gem 'webmock'
end

group :development, :staging do
  gem 'rack-mini-profiler', require: false
end
