source 'https://rubygems.org'

gem 'rake'
gem 'hanami',       '~> 1.0'
gem 'hanami-model', '~> 1.0'


group :development do
  gem 'sqlite3'
  gem 'wdm', '>=0.1.0'
  #gem 'shotgun'
end

group :test, :development do
  gem 'dotenv', '~> 2.0'
end

group :test do
  gem 'minitest'
  gem 'capybara'
end

group :production do
  gem 'puma'
  gem 'pg'
end
