# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

gem 'rails', '~> 6.1.4'

gem 'bootsnap', '>= 1.12', require: false
gem 'dotenv-rails', '~> 2.7'
gem 'pg', '>= 0.18', '< 2.0'

gem 'active_model_serializers', '~> 0.10.13'
gem 'authlogic', '~> 6.4'
gem 'bcrypt', '~> 3.1.16'
gem 'faraday', '~> 1.10.0'
gem 'google-api-client', '~> 0.50', require: false
gem 'google-cloud-storage', '~> 1.37', require: false
gem 'firebase', '~> 0.2.8', require: false
gem 'oj', '~> 3.13'
gem 'puma', '~> 5.5'
gem 'rack-cors', '~> 1.1'
gem 'rubocop', '~> 1.31.2', require: false
gem 'json_schemer', '~> 0.2.18'
gem 'paper_trail', '~> 12.3'
gem 'interactor', '~> 3.1', '>= 3.1.2'
gem 'ruby-progressbar', '~> 1.11', require: false
gem 'pundit', '~> 2.1'
gem 'algoliasearch-rails', '~> 2.2'
gem 'carrierwave', '~> 2.2'
gem 'carrierwave-vips', '~> 1.2'
gem 'fog-google', '~> 1.17'
gem 'anycable-rails', '~> 1.3'
gem 'redis', '>= 4.0'
gem 'docile', '~> 1.4'
gem 'google-id-token', '~> 1.4.2', require: false
gem 'administrate', '~> 0.17.0'
gem 'concurrent-ruby', '~> 1.1'

gem 'activerecord6-redshift-adapter', '~> 1.2', '>= 1.2.1'
gem 'activerecord-import', '~> 1.3', require: false

gem 'data_migrate', '~> 8.0'

# sentry
gem 'sentry-ruby', '~> 5.3'
gem 'sentry-rails', '~> 5.3'
gem 'sentry-sidekiq', '~> 5.3'

# Sidekiq
gem 'sidekiq', '~> 6.5.1'
gem 'sidekiq_alive', '~> 2.1.4'
gem 'sidekiq-limit_fetch', '~> 4.2'

gem 'slack-notifier', '~> 2.4'

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

# datadog should be required after all supported services
gem 'ddtrace', '~> 1.2.0', require: 'ddtrace/auto_instrument'
# needed for datadog profiling
gem 'google-protobuf', '~> 3.21', '>= 3.21.4'

# helper with country codes
gem 'iso_country_codes', '~> 0.7'

# Import partner stories
gem "net-sftp", require: false
gem "ed25519", require: false
gem "bcrypt_pbkdf", require: false
gem "im_onix", "~> 1", require: false
gem 'epub-parser', require: false, git: 'https://github.com/inkitt/epub-parser.git', branch: 'master'

group :development, :test do
  gem 'factory_bot_rails'
  gem 'faker', '~> 2.19'
  gem 'pry-byebug'
  gem 'rspec-rails', '~> 5.0'
  gem 'guard-rspec', require: false
  gem 'rswag-api', '~> 2.4'
  gem 'rswag-specs', '~> 2.4'
end

group :development do
  gem 'annotate', '~> 3.1'
  gem 'listen', '>= 3.0.5', '< 3.8'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'web-console', '>= 3.3.0'
  gem "letter_opener"
end

group :test do
  gem 'codecov', require: false
  gem 'simplecov', require: false
  gem 'shoulda-matchers', '~> 5.1'
  gem 'rspec-sidekiq', '~> 3.1.0'
  gem 'timecop', '~> 0.9.4'
  gem 'webmock', '~> 3.14'
end
