source 'https://rubygems.org'

git_source(:github) { |repo_name| "https://github.com/#{repo_name}.git" }

branch = ENV.fetch('SOLIDUS_BRANCH', 'master')
gem 'solidus', github: 'solidusio/solidus', branch: branch

gemspec

gem 'pry'

group :test do
  gem 'ffaker'
  gem 'mysql2'
  gem 'pg'
  gem 'sqlite3'
  gem 'vcr'
  gem 'webmock'
end

gem 'activemerchant', github: 'activemerchant/active_merchant'
