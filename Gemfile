# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo_name| "https://github.com/#{repo_name}.git" }

gem 'puma', '~> 3.0'
gem 'rails', '~> 5.0.7', '>= 5.0.7.2'

# DATABASE
gem 'activerecord-session_store', '~> 1.1.3'
gem 'pg', '>= 0.18', '< 2.0'

# AUTHENTICATION
gem 'omniauth_openid_connect', github: 'm0n9oose/omniauth_openid_connect', tag: 'v0.3.5'
gem 'omniauth-openid_connect-providers', github: 'thinkific/omniauth-openid_connect-providers', branch: 'main'

group :development, :test do
  gem 'dotenv-rails', '~> 2.7.6'
  gem 'pry-byebug'
end

group :development do
  gem 'listen', '~> 3.0.5'
  gem 'rubocop', require: false
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
