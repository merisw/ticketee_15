source 'https://rubygems.org'

gem 'rails', '3.2.8'
gem 'dynamic_form', '1.1.4'
gem 'devise', '2.1.0.rc'
gem 'cancan', '1.6.7'
gem 'paperclip', '2.7.0'
gem 'searcher', :git => "git://github.com/radar/searcher"
gem 'omniauth-twitter', git: "https://github.com/arunagw/omniauth-twitter.git"
gem 'omniauth-github', git: "https://github.com/intridea/omniauth-github"

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'
gem 'debugger'

group :test, :development do
  gem 'gmail', '0.4.0'
  gem 'rspec-rails', '~> 2.9'
  gem 'sqlite3'
end

group :development do
  gem 'capistrano'
end

group :test do
  gem 'capybara', '1.1.2'
  gem 'factory_girl', '2.6.4'
  gem 'email_spec', '1.2.1'
  gem 'database_cleaner'
  gem 'launchy'
end

group :production do
  gem 'therubyracer'
  gem 'pg'
end
