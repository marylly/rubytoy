source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

ruby '2.4.1'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails',        '~> 5.1.3'

gem 'sqlite3'

gem 'materialize-sass', '~> 0.100.1'

# Use Puma as the app server
gem 'puma',         '~> 3.7'
# Use SCSS for stylesheets
gem 'sass-rails',   '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier',     '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks',   '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder',     '~> 2.5'

# Simple wrapper for safely handling passwords.
gem 'bcrypt',       '3.1.11'
# Generate fake data: names, addresses, phone numbers, etc.
gem 'faker',        '1.8.4'

# recursos para paginação dos usuários
gem 'will_paginate',  '3.1.0'
gem 'bootstrap-will_paginate',  '0.0.10'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
end
group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# learn-rails
gem 'bootstrap-sass'
gem 'gibbon'
gem 'high_voltage'
gem 'jquery-rails'
group :development do
  gem 'better_errors'
  gem 'rails_layout'
  gem 'logger', '~> 1.2', '>= 1.2.8'
end
group :development, :test do
  # gem 'sqlite3'
  gem 'pg'
end
group :production do
  gem 'pg'
end
group :test do
  gem 'minitest-spec-rails'
  gem 'logger', '~> 1.2', '>= 1.2.8'
end