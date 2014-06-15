source 'https://rubygems.org'

gem 'rails', '>= 4.1.1'

group :development do
  gem 'hirb'
end

group :development, :test do
  gem 'minitest'
  gem 'factory_girl_rails'
  gem 'rspec-rails'
  gem 'capistrano', '~> 3.2.0'
  gem 'capistrano-bundler', '~> 1.1.2'
  gem 'capistrano-rails', '~> 1.1.1'
  gem 'capistrano-rbenv', '~> 2.0'
  gem 'colored'
  gem 'spring'
end

group :production do
  gem 'dalli'
  gem 'therubyracer'
end

# # Used for import or sync content.  We don't need
# # these loaded in the web app.
gem 'mailman',    :require => false