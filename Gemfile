source 'https://rubygems.org'
ruby '2.5.1'

gem 'rails', '5.1.4'
gem 'pg'
gem 'dumper'

gem 'scrivito', '~> 1.13.0'
gem 'scrivito_section_widgets'
gem 'scrivito_teaser_widget'

gem 'coffee-rails'
gem 'jbuilder'
gem 'jquery-rails'

gem 'simple_grid_rails'
gem "bootstrap-sass"
gem 'sass-rails'
gem 'uglifier'
gem 'font-awesome-rails'
gem 'haml-rails'
gem 'rails-html-sanitizer', '~> 1.0.4'

# For redirection
gem 'rack-host-redirect'

# For SSL and CORS
gem 'secure_headers'

# Rendering legal documents
gem 'kramdown'

gem 'faraday'
# TODO: Delete this if the following issue is fixed
# https://github.com/bundler/bundler/issues/5332
gem 'faraday_middleware', '0.10'

gem 'koala'

gem 'rack-user_agent'

gem 'rack-attack'

gem 'google_drive'

gem 'lazy_high_charts'

group :development do
  gem 'web-console'
  gem 'spring'
  gem 'listen'
  gem 'rack-mini-profiler', require: false
  gem 'flamegraph', require: false
  gem 'stackprof', require: false
  gem 'memory_profiler', require: false
end

group :development, :test do
  gem 'pry-rails'
  gem 'pry-byebug'
  gem 'pry-doc'
  gem 'pry-stack_explorer'
  gem 'rake'
  gem 'travis'
  gem 'minitest-retry'
  gem 'rspec-retry'

  gem 'selenium-webdriver'
  gem 'capybara'
  gem 'rspec-rails', '~> 3.5'

  gem 'dotenv-rails'
end

group :test do
  gem 'rails-controller-testing'
end
