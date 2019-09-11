source 'https://rubygems.org'

ruby '2.6.2'

gem 'rails', git: 'https://github.com/rails/rails.git'
gem 'pg'

# assets
gem 'sass-rails'
gem 'uglifier'
gem 'coffee-rails'
gem "premailer-rails"

source "https://rails-assets.org" do
  gem "rails-assets-jquery-ujs"
  gem "rails-assets-jquery2"
end

# views
gem "active_link_to"
gem "inky-rb", require: "inky"
gem "meta-tags"
gem "simple_form"
gem "slim"

# all other gems
gem 'puma'
gem 'bootsnap'

# all other gems
gem "decent_decoration"
gem "decent_exposure"
gem "devise"
gem "draper"
gem "health_check"
gem "interactor"
gem "kaminari"
gem "pundit"
gem "responders"

group :development, :test do
  gem 'byebug'
end

group :development do
  gem 'web-console'
  gem 'listen'
  gem 'spring'
  gem 'spring-watcher-listen'
end

group :test do
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  gem 'chromedriver-helper'
end
