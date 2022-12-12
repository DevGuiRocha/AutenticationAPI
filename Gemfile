source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.0'

gem 'pg'

gem 'rails', '~> 6.0.6'

gem 'sqlite3', '~> 1.4'

gem 'puma', '~> 4.1'

gem 'bootsnap', '>= 1.4.2', require: false

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'listen', '~> 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem "letter_opener", "~> 1.8"
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem "devise_token_auth", "~> 1.2"

gem "active_model_serializers", "~> 0.10.13"
