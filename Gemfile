source 'https://rubygems.org'

# https://github.com/mime-types/ruby-mime-types/issues/94
# This can be removed once all gems depend on > 3.0
gem 'mime-types', '~> 2.99', require: 'mime/types/columnar'

gem 'rails', '~> 7.0.8', '>= 7.0.8.1'
gem 'rails-i18n', '>= 7.0.1'

gem 'autoprefixer-rails'
gem 'aws-sdk', '~> 2.2'
gem 'builder'
gem 'clearance', '>= 1.14.2'
gem 'clearance-deprecated_password_strategies', '>= 1.10.2'
gem 'daemons'
gem 'dalli'
gem 'delayed_job'
gem 'delayed_job_active_record'
gem 'doorkeeper', '>= 4.0.0'
gem 'dynamic_form'
gem 'gchartrb', require: 'google_chart'
gem 'gravtastic'
gem 'high_voltage'
gem 'highline'
gem 'honeybadger'
gem 'http_accept_language'
gem 'jquery-rails', '>= 4.2.0'
gem 'mail'
gem 'multi_json'
gem 'newrelic_rpm'
gem 'paul_revere', '~> 3.3', '>= 3.3.0'
gem 'pg'
gem 'psych', '~> 2.0.12'
gem 'rack', '>= 2.2.8.1'
gem 'rdoc', '>= 6.3.4.1'
gem 'rest-client', require: 'rest_client'
gem 'shoryuken', '~> 2.0.2', require: false
gem 'statsd-instrument', '~> 2.0.6'
gem 'uglifier', '>= 1.0.3'
gem 'unicorn'
gem 'validates_formatting_of'
gem 'will_paginate'
gem 'elasticsearch-model', '~> 0.1.7'
gem 'elasticsearch-rails', '~> 0.1.7'
gem 'elasticsearch-dsl', '~> 0.1.2'
gem 'xml-simple'
gem 'yajl-ruby', require: 'yajl'
gem 'compact_index', '~> 0.11.0'
gem 'sprockets-rails', '~> 3.2.0'
gem 'rack-attack', '>= 5.1.0'

group :development, :test do
  gem 'rubocop', require: false
  gem 'toxiproxy', '~> 0.1.3'
end

group :development do
  gem 'rails-erd'
end

group :test do
  gem 'minitest', require: false
  gem 'capybara', '>= 2.8.0'
  gem 'factory_girl_rails', '>= 4.8.0'
  gem 'launchy'
  gem 'rack-test', '>= 0.7.0', require: 'rack/test'
  gem 'mocha', require: false
  gem 'bourne', require: false
  gem 'shoulda', require: false
end

group :development, :deploy do
  gem 'capistrano', '~> 3.0', require: false
  gem 'capistrano-rails', '~> 1.1', require: false
  gem 'capistrano-bundler', '~> 1.1', require: false
end
