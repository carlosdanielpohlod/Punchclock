# frozen_string_literal: true

source 'https://rubygems.org'

git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.5'

gem 'rails', '~> 6.0.4'

gem 'bootsnap', require: false

gem 'autoprefixer-rails', '~> 10.2.4.0'
gem 'pg', '~> 1.2'
gem 'unicorn'
gem 'sprockets'
gem 'cancancan', '~> 3.1'
gem 'carrierwave', '~> 2.2.1', github: 'carrierwaveuploader/carrierwave'
gem 'devise', '~> 4.7.3'
gem 'devise-two-factor'
gem 'rqrcode'
gem 'jquery-rails'
gem 'jquery-ui-rails'
gem 'sass-rails'
gem 'simple_form', '~> 5.0'
gem 'uglifier'
gem 'activeadmin', '~> 2.8.1'
gem 'draper'
gem 'draper-cancancan'
gem 'rails-i18n'
gem 'webpacker', '~> 5.1'
gem 'holidays', '~> 8.3'
gem 'kaminari'
gem 'coffee-script', '~> 2.4', '>= 2.4.1'
gem 'spreadsheet'
gem 'httparty'
gem 'github_api', '~> 0.18.2'

gem 'ransack', '~> 2.3'

gem 'sidekiq'

gem 'rollbar'

gem 'chartkick'

gem 'normalize-rails', '~> 4.1.1'
gem 'validates_timeliness', '~> 5.0.0.beta1'
gem 'enumerize', '~> 2.3.1'
gem 'jquery_mask_rails', '~> 0.1.0'
gem 'active_admin_theme'
gem 'font-awesome-sass', '~> 5.13'
gem 'bootstrap', '~> 4.5'
gem 'jquery-easing-rails'

gem 'active_skin'
gem 'active_admin_flat_skin'
gem 'aasm', '~> 5.0', '>= 5.0.8'

# SSL (https://github.com/pixielabs/letsencrypt-rails-heroku)
gem 'platform-api', github: 'heroku/platform-api'
gem 'letsencrypt-rails-heroku', group: 'production'

group :test do
  gem 'capybara'
  gem 'shoulda-matchers'
  gem 'simplecov', require: false
  gem 'codeclimate-test-reporter', require: nil
  gem 'capybara-selenium'
  gem 'selenium-webdriver'
  gem 'rails-controller-testing'
  gem 'capybara-screenshot'
  gem 'vcr'
  gem 'webmock'
end

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'bullet'
  gem 'certified'
  gem 'letter_opener'
  gem 'letter_opener_web', '~> 1.4'
  gem 'foreman'
  gem 'web-console', '~> 4.0'
  gem 'listen', '~> 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0'
end

group :development, :test do
  gem 'factory_bot_rails'
  gem 'faker', '~> 2.14.0'
  gem 'rspec-rails'
  gem 'pry-rails'
  gem 'pry-remote', '~> 0.1.8'
  gem 'dotenv-rails', '~> 2.7'
  gem 'rubocop', require: false
  gem 'rubocop-faker', '~> 1.1'
end

group :production, :staging do
  gem 'passenger', '~> 6.0'
end
