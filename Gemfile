source 'https://rubygems.org'
source 'https://rails-assets.org'


gem 'rails', '4.1.6'
gem 'sass-rails', '~> 4.0.3'
gem 'slim-rails'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'omniauth'
gem 'omniauth-github'

gem 'jquery-rails'
gem 'turbolinks', '~> 2.4.0'
gem 'jquery-turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.2.2'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0',          group: :doc

gem 'ransack', '~> 1.5.1'
gem 'squeel', '~> 1.2.2'

gem 'activeadmin', github: 'gregbell/active_admin'

gem 'simple_form', github: 'plataformatec/simple_form'
gem 'friendly_id', '~> 5.0.4'

gem 'cancancan', '~> 1.9'

gem 'unicorn'
gem 'foreman'

## API

# Assets
gem 'bootstrap-sass', '~> 3.2.0.2'
gem 'rails-assets-bootswatch-scss', '~> 3.2.0.3'
gem 'font-awesome-sass', '~> 4.2.0'

## Faye
# gem 'faye-websocket'
gem 'pusher'
gem 'vuejs-rails'

gem 'sqlite3'
group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'spring'
  # Deploy
  gem 'mina'
  gem 'mina-unicorn', require: false
end

group :provisioning do
  gem 'itamae'
  gem 'serverspec'
end

group :test do
  gem 'rspec-rails'
  gem 'database_cleaner'
  gem 'capybara'
  gem 'factory_girl_rails'
end

group :production, :staging do
  gem 'pg'
end

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'


# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development



# Use debugger
# gem 'debugger', group: [:development, :test]

