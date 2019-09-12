source "https://rubygems.org"

ruby "2.6.2"

gem "pg"
gem "rails", git: "https://github.com/rails/rails.git"

# assets
gem "coffee-rails"
gem "premailer-rails"
gem "sass-rails"
gem "uglifier"

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
gem "bootsnap"
gem "puma"

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
  gem "brakeman", require: false
  gem "bundler-audit", require: false
  gem "byebug"
  gem "coffeelint"
  gem "dotenv-rails"
  gem "factory_bot"
  gem "faker"
  gem "jasmine", "> 2.0"
  gem "jasmine-jquery-rails"
  gem "pry-rails"
  gem "rspec-rails", "~> 3.5"
  gem "rubocop", require: false
  gem "rubocop-rspec", require: false
  gem "scss_lint", require: false
  gem "slim_lint", require: false
end

group :development do
  gem "letter_opener"
  gem "listen"
  gem "spring"
  gem "spring-watcher-listen"
  gem "web-console"
end

group :test do
  gem "capybara"
  gem "chromedriver-helper"
  gem "database_cleaner"
  gem "poltergeist"
  gem "rspec-its"
  gem "selenium-webdriver"
  gem "shoulda-matchers"
  gem "terminal-notifier-guard"
  gem "webmock", require: false
end
