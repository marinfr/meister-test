source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.7'

gem 'rails', '~> 6.0.3', '>= 6.0.3.2'
gem 'mysql2', '>= 0.4.4'
gem 'puma', '~> 4.1'
gem 'sass-rails', '>= 6'
gem 'webpacker', '~> 4.0'
gem 'redis', '~> 4.0'
gem 'devise'
gem 'haml'
gem 'will_paginate'
gem 'graphql'
gem 'bootsnap', '>= 1.4.2', require: false
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

group :development, :test do
  gem 'pry-byebug'
  gem 'rspec-rails', '~> 4.0.1'
  gem 'factory_bot_rails'
end

group :test do
  gem 'simplecov', require: false
  gem 'rails-controller-testing'
  gem 'shoulda-matchers', '~> 4.0'
end

group :development do
  gem 'graphiql-rails'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end
